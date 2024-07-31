# addEventListener

The **`addEventListener()`** method sets up a function that will be called whenever the specified event is delivered to the target.

```lua
document.addEventListener(eventName: String,callback: function)
```

Examples

```lua
document.addEventListener("DOMContentLoaded",function()
    print("DOM Loaded")
end)
```

```lua
document.addEventListener("customEvent",function(arg1)
    print("Custom Event Loaded!", arg1)
end)

document.dispatchEvent("customEvent", "test")
```
