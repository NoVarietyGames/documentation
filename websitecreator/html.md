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

# HTML Interpreter

{% hint style="danger" %}
Not all HTML code will work with this interpreter
{% endhint %}

{% hint style="warning" %}
This documentation will not include CSS
{% endhint %}

Most HTML code will work with this custom built interpreter, Not everything will because of the way it was built



Code some HTML the same way you would create a website on the web

Here is some **example** HTML code

<pre class="language-html"><code class="lang-html">&#x3C;html name="action" t="poop">
Create data attributes by just including the key equal to value in the tag
&#x3C;body id="id" action="test">

There are no style attributes at the moment. You need to use CSS
&#x3C;p id="test">This site is built entirely with HTML with the new custom HTML compiler. You can even use CSS with it!&#x3C;/p>
<strong>
</strong><strong>Anything not in a tag is a comment and will NOT BE READ BY THE Interpreter
</strong><strong>
</strong><strong>For CSS classes use className instead of Class
</strong>&#x3C;p className="class">class&#x3C;/p>

Instead of JS scripts, it is now LUA scripts!
Some cool example code, better explained in the LUAScript section
<strong>&#x3C;script src="main.lscript">&#x3C;/script>
</strong>&#x3C;/body>
&#x3C;/html>
</code></pre>

So far here are all the valid tags

<table><thead><tr><th>Tag</th><th data-hidden>Roblox Element</th><th data-hidden></th></tr></thead><tbody><tr><td>html</td><td>frame</td><td></td></tr><tr><td>head</td><td>frame</td><td></td></tr><tr><td>body</td><td></td><td></td></tr><tr><td>div</td><td></td><td></td></tr><tr><td>span</td><td></td><td></td></tr><tr><td>p</td><td></td><td></td></tr><tr><td>h1</td><td></td><td></td></tr><tr><td>h2</td><td></td><td></td></tr><tr><td>h3</td><td></td><td></td></tr><tr><td>h4</td><td></td><td></td></tr><tr><td>label</td><td></td><td></td></tr><tr><td>input</td><td></td><td></td></tr><tr><td>textarea</td><td></td><td></td></tr><tr><td>button</td><td></td><td></td></tr><tr><td>a</td><td></td><td></td></tr><tr><td>img</td><td></td><td></td></tr><tr><td>ul</td><td></td><td></td></tr><tr><td>ol</td><td></td><td></td></tr><tr><td>li</td><td></td><td></td></tr><tr><td>table</td><td></td><td></td></tr><tr><td>tr</td><td></td><td></td></tr><tr><td>td</td><td></td><td></td></tr><tr><td>th</td><td></td><td></td></tr><tr><td>form</td><td></td><td></td></tr><tr><td>nav</td><td></td><td></td></tr><tr><td>footer</td><td></td><td></td></tr><tr><td>header</td><td></td><td></td></tr><tr><td>section</td><td></td><td></td></tr><tr><td>article</td><td></td><td></td></tr><tr><td>aside</td><td></td><td></td></tr><tr><td>details</td><td></td><td></td></tr><tr><td>summary</td><td></td><td></td></tr><tr><td>main</td><td></td><td></td></tr><tr><td>mark</td><td></td><td></td></tr><tr><td>meter</td><td></td><td></td></tr><tr><td>progress</td><td></td><td></td></tr><tr><td>time</td><td></td><td></td></tr><tr><td>small</td><td></td><td></td></tr><tr><td>cite</td><td></td><td></td></tr><tr><td>code</td><td></td><td></td></tr><tr><td>strong</td><td></td><td></td></tr><tr><td>noscript</td><td></td><td></td></tr><tr><td>style</td><td></td><td></td></tr><tr><td>link</td><td></td><td></td></tr><tr><td>meta</td><td></td><td></td></tr><tr><td>title</td><td></td><td></td></tr><tr><td>script</td><td></td><td></td></tr><tr><td>center</td><td></td><td></td></tr></tbody></table>
