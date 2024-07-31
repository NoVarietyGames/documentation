---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# createNode

The method **`createNode()`** creates the HTML element specified by _tagName._ Within the arguments you may also include attributes and the text included.

<pre class="language-javascript"><code class="lang-javascript"><strong>document.createNode(TagName,AttributeTable,Text)
</strong></code></pre>

Examples

```lua
document.createNode("p",{id="id",style="color:red"},"This is a paragraph element!")
```

```javascript
document.createNode("frame",{["frame-data"]="E_E",style="background-color:red"},"<p>Paragraph within the frame</p>")
```

