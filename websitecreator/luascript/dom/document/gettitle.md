# getTitle

The **`getTitle`** method gets the current title of the document. **`setTitle`** defines the document's title that is shown in a browser's title bar or a page's tab.

<pre class="language-lua"><code class="lang-lua"><strong>document.getTitle(): Title
</strong></code></pre>

Examples

```lua
print(document.getTitle())
```

```lua
document.addEventListener("DOMContentLoaded",function()
    print("Title is", document.getTitle())
end)
```
