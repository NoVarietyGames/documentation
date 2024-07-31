# removeEventListener

The **`removeEventListener()`** method removes any Event Listener using their eventID

**Returns** EventId

```lua
document.removeEventListener(eventName: String, EventId: EventId): void
```

Examples

<pre class="language-lua"><code class="lang-lua">local eventid = document.addEventListener("DOMContentLoaded",function(timeTaken)
    -- DOMContentLoaded gives you the time taken to load the DOM which uses os.clock
<strong>    -- This only runs ONCE and it's when the page is first loaded.
</strong>    print("DOM Took " .. tostring(timeTaken) .. " to load!"
end)
document.removeEventListener(eventid)

</code></pre>

```lua
local eventid = document.addEventListener("customEvent",function(arg1)
    print("Custom Event Loaded!", arg1)
end)
document.removeEventListener(eventid)

-- Event will dispatch but no print will occur
document.dispatchEvent("customEvent", "test")
```
