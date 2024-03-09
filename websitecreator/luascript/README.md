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

# LUAScript

{% hint style="info" %}
Basic LUA and Some Web Development Knowledge required
{% endhint %}

Let's take a look at the script shown in [html.md](../html.md "mention")

```lua
delay(1)
local name = window.input("What is your name?","My name is ...")
local elm = document.createNode("p",{
style="color:red"
},string.format("Welcome %s",name))
document.querySelector("body").appendChild(elm)
elm.style="color:blue"
print("Updating")
--document.innerHTML ="<p>CHANGE INNER HTML</p>"
elm.style="color:red"
--elm.innerText = "Test!"
print("Done!")
```

LUAScript uses native LUA Functions but also takes some custom functions built in

LUAScript Functions

<table><thead><tr><th>Function</th><th>Documentation</th><th data-hidden></th></tr></thead><tbody><tr><td>delay</td><td><a data-mention href="delay.md">delay.md</a></td><td></td></tr><tr><td>Document Elements</td><td><a data-mention href="dom/">dom</a></td><td></td></tr><tr><td></td><td></td><td></td></tr></tbody></table>
