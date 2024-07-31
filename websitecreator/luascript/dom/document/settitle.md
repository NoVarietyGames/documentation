# setTitle

The **`getTitle`** method gets the current title of the document. **`setTitle`** defines the document's title that is shown in a browser's title bar or a page's tab.

<pre class="language-lua"><code class="lang-lua"><strong>document.setTitle("Test")
</strong></code></pre>

Examples

```lua
document.setTitle("New Title!")
```

```lua
document.addEventListener("DOMContentLoaded",function()
    document.setTitle("New Title!")
end)
```
