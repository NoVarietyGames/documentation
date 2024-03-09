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

# setTimeout

setTimeout is just LUA native `delay` expect it does not yield the current running thread

setTimeout takes **2** arguments, the function and numeric timeout in seconds

<pre class="language-lua"><code class="lang-lua"><strong>local Age = 18
</strong><strong>print("You are " .. Age .. " years old!")
</strong>setTimeout(function()
    Age = 23
    print("You are now " .. Age .. " years old!")
end, 5)
print("You are still " .. Age .. " years old!")
</code></pre>

