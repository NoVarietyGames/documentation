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

# cloneNode

The **`cloneNode()`** method clones a specific element and returns it



**Example**

```lua
local elm = document.querySelector("body").querySelector("#clone")
local clonedElm = document.cloneNode(elm)
document.querySelector("body").appendChild(clonedElm)
```
