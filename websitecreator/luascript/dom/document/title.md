# title

{% hint style="danger" %}
This property currently does not exist. Use [gettitle.md](gettitle.md "mention") & [settitle.md](settitle.md "mention")
{% endhint %}

The **`document.title`** property gets or sets the current title of the document. **`document.title`** defines the document's title that is shown in a browser's title bar or a page's tab.

<pre class="language-lua"><code class="lang-lua"><strong>document.title = "String"
</strong></code></pre>

Examples

```lua
document.title = "New Title!"
```

```lua
document.addEventListener("DOMContentLoaded",function()
document.title = "DOM Loaded!"
end)
```
