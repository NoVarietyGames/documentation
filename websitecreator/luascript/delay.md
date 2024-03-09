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

# delay

Delay is just LUA native wait

Delay takes **1** numeric argument called seconds. Delay yields the entire thread until the time is completed.

```lua
print("Hello!")
delay(1) -- wait 1 second
print("Hello after 1 second") -- Prints after 1 second
```
