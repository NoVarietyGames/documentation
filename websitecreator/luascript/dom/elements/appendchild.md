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

# appendChild

The **`appendChild()`** method adds a Element to the end of the list of children of a element.



**Example**

<pre class="language-lua"><code class="lang-lua">local name = window.input("What is your name?","My name is ...")
<strong>local elm = document.createNode("p",{style="color:red"},string.format("Welcome %s",name))
</strong>document.querySelector("body").appendChild(elm)
</code></pre>
