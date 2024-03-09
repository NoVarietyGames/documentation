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

# Terminal Language

{% hint style="danger" %}
Some Basic LUA functions may not work, they will be added in the feature.
{% endhint %}

Welcome! Here is some WIP documentation of the Terminal in ROBLOS



Terminal commands are created using the vanilla version of Lua

Here is an example of the $$ls$$ command

```lua
--#DESCRIPTION: Displays a list of files and subdirectories in a directory\nUsage: ls
modules.echo.off()
local folders = modules.folder.getFolder(modules.folder.getDir())
local stuff = {}
for name,_ in pairs(folders) do
	table.insert(stuff,name)
end
modules.echo.on()
	
print(table.concat(stuff,","))
```

## So what is going on?

All programs must start with a description, to start your first program go to the notepad and start it off with the code below.

```lua
--#DESCRIPTION: Explain what your program does
```

Next let's get used to our tools

There is a new global variable called $$modules$$&#x20;

These variables allow you to interact with the OS, some examples could be getting the current directory and changing it as well.



Current Modules Implemented&#x20;

#### Folder Modules

```lua
modules.folder.isValid(path: String): Boolean
-- Checks if path is a valid Path not if it exist.

modules.folder.changeDir(path: String): Void
--Changes terminal directory

modules.folder.getDir(): String
-- Return current Directory path

modules.folder.getFolder(path: String): Table
-- Returns all content within that path as a table, this includes the metadata of that current file

modules.folder.copy(filePath: String, NewPath: String): Boolean
-- Copy a file NOT A DIRECTORY to a new path

```

#### Echo Module

<pre class="language-lua"><code class="lang-lua"><strong>modules.echo.off()
</strong>-- Disables any print,warn,usage,error function

modules.echo.on()
-- Enables all print,warn,usage,error function

modules.echo.off()
-- Disables any print,warn,usage,error function

modules.echo.toggle()
-- Toggles all print,warn,usage,error function

modules.echo.force()
-- Force any print,warn,usage,error to be enabled or disabled function


</code></pre>

Now you know, the basics of the terminal language.&#x20;

As of now this is still a WIP and more modules are getting added along with more commands. This documentation will be changed to include more information but of now.

That's all folks!

