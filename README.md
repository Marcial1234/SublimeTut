# Perfect Workflow with Sublime Text 3


## Introduction
Welcome to an overview of Sublime Text 3 most useful shortcuts and tips. Sublime Text is a cross-platform text editor, and in the recent years it has transitioned from a hipster wed developer widget to a must-have professional tool for the modern software developer. This manual will cover essential shortcuts and add-ons that Sublime Text provides that''ll increase your productivity, smoothen your workflow, and decrease projects'' duration/time more than any other software you''ve used in the past. I''ll start with the assuption that you posses prior knowledge in programming languages, and common development workflow scenarios. If you don'' t, stop right now and grab a copy of Nathan Caldwell''s 'How to write a Java Program on Mac OS X' & Austin Seber''s 'Eclipse IDE for beginners' to acquire the essentials from which this manual builds upon.



### Snippets
```html
<snippet>
  <content><![CDATA[
    def ${1:function}(${4:params}):
      print 'Hello, ${2:this} is a ${3:snippet}.'
  ]]></content>
  <!-- Optional: Tab trigger to activate the snippet -->
  <tabTrigger>hellow</tabTrigger>
  <!-- Optional: Scope the tab trigger will be active in -->
  <scope>source.python</scope>
  <!-- Optional: Description to show in the menu -->
  <description>My Fancy Snippet</description>
</snippet>
```

Will create
```python
def function():
  print 'Hello, this is a snippet.'
```
