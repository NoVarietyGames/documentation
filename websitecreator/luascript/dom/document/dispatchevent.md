# dispatchEvent

The **`dispatchEvent()`** method sends an Event to the object, invoking the affected event listeners in the appropriate order.&#x20;

```lua
document.dispatchEvent(eventName: String, ...arguments): void
```

Examples

```lua
document.addEventListener("customEvent1",function(arg1,arg2,arg3)
    print(arg1,arg2,arg3)
end)
document.dispatchEvent("customEvent1", "test1","test2","test3")
```

<pre class="language-lua"><code class="lang-lua">document.addEventListener("UserCommented",function(username,data)
    print(username .. " has commented on post id:" .. data.postid ". Here is the data!",data)
end)
document.dispatchEvent("UserCommented","Roblox",{postid: 5,message:"This is cool!!",date:"Fri Jul 26 01:12:22 2024", upvotes: 9000, downvotes:200})
<strong>document.dispatchEvent("UserCommented","PFearr",{postid: 0,message:"Hello!",date:"Wed Jul 31 01:12:22 2024", upvotes: 999999, downvotes:-99999})
</strong>
</code></pre>
