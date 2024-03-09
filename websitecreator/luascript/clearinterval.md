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

# clearInterval

clearInterval stops a currently running Interval using it's ID

clearInterval takes **1** arguments, the timeout ID

```lua
local Age = 1
local interval = setInterval(function()
    Age = Age + 1
    print("You are " .. Age .. " years old")
end, 5) -- every 5 seconds this will print the current Age

delay(20) -- wait 20 seconds
clearInterval(interval) -- stop the current running interval
print("Final age " .. Age)
```

