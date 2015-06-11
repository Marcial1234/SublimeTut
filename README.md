# Sublime Text 3


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
def ${1:function}(${4:params}):
  print 'Hello, ${2:this} is a ${3:snippet}.'
```
