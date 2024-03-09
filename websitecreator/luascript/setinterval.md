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

# setInterval

setInterval is just LUA native `delay` expect it runs infinitely every timeout

setInterval takes **2** arguments, the function and numeric timeout in seconds

setInterval **returns** the **interval timeout ID,** you can use this to stop the interval using [clearinterval.md](clearinterval.md "mention")

```lua
local Age = 1
setInterval(function()
    Age = Age + 1
    print("You are " .. Age .. " years old")
end, 5) -- every 5 seconds this will print the current Age
```

