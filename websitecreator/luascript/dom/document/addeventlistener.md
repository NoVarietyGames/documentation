# addEventListener

The **`addEventListener()`** method sets up a function that will be called whenever the specified event is delivered to the target.

```lua
document.addEventListener(eventName: String,callback: function)
```

Examples

<pre class="language-lua"><code class="lang-lua">document.addEventListener("DOMContentLoaded",function(timeTaken)
    -- DOMContentLoaded gives you the time taken to load the DOM which uses os.clock
<strong>    -- This only runs ONCE and it's when the page is first loaded.
</strong>    print("DOM Took " .. tostring(timeTaken) .. " to load!"
end)

document.addEventListener("DOMContentRefreshed",function(timeTaken)
    -- DOMContentRefreshed gives you the time taken to load the DOM which uses os.clock
    -- This only runs every time you make a change using LuaScript which reloads the
    -- entire DOM
    print("DOM Took " .. tostring(timeTaken) .. " to load!"
end)
</code></pre>

```lua
document.addEventListener("customEvent",function(arg1)
    print("Custom Event Loaded!", arg1)
end)

document.dispatchEvent("customEvent", "test")
```
