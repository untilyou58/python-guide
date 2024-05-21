---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides, markdown enabled
title: Python from Scratch
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply any unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: fade-out
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
---

# Python from Scratch

A beginner-friendly guide to Python programming.

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<!-- <div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div> -->

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---

# Tools for writing and running code

We will go over a few tools that may be used to write and execute Python code below

- **Default Interactive Environment**
- **Vscode**
- **PyCharm**

<br>
<br>


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
transition: fade-out
level: 2
class: py-50
---

# Default Interactive Environment

Launch the "Command Prompt" or "PowerShell" program on Windows, or the "Terminal" program on MacOS or Linux, and type `python` to enter the Python interactive environment.


---
level: 2
class: py-50
transition: fade-out
---


```md
$ python
Python 3.12.3
Type "help", "copyright", "credits" or "license" for more information.
>>> 1 + 1
2
>>> 2 + 2
4
>>> 4 + 1
5
```


---
transition: fade-out
class: py-50
---


To exit the Python interactive environment, type `exit()` or `quit()` and press Enter
You can also use the <kbd>Ctrl</kbd> + <kbd>Z</kbd> key combination on Windows or the <kbd>Ctrl</kbd> + <kbd>D</kbd> key combination on MacOS or Linux to exit the Python interactive environment.


---
class: py-50
---


```md
>>> exit()
$
```


---
transition: fade-out
level: 2
---

# Vscode

Microsoft created Visual Studio Code, an application for editing code that works with Linux, macOS, and Windows.

<!-- Insert image -->
<img src="https://upload.wikimedia.org/wikipedia/commons/9/9a/Visual_Studio_Code_1.35_icon.svg" alt="Vscode" width="200" class="m-4">

We can find the [download link](https://code.visualstudio.com/download) for Vscode on the official website of Vscode , as shown in the figure below.

Extensive support for Python is provided by Vscode, including syntax highlighting, code completion, and debugging. The Python extension for Vscode is available for download from the [Vscode Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-python.python).


---
transition: fade-out
level: 2
---

# PyCharm

PyCharm is an integrated development environment (IDE) provided by a Czech company called JetBrains for the Python language. The so-called integrated development environment usually refers to a development tool that provides a series of powerful functions and convenient operations such as writing code, running code, debugging code, analyzing code, version control, and so on.

<!-- Insert image -->
<img src="https://upload.wikimedia.org/wikipedia/commons/1/1d/PyCharm_Icon.svg" alt="PyCharm" width="200" class="m-4">

We can find the [download link](https://www.jetbrains.com/pycharm/download/) for PyCharm on the official website of JetBrains, as shown in the figure below.


---
level: 2
transition: fade-out
---

# Hello World

<v-click>
```py {all}
print('hello, world')
```
</v-click>

<br>

<v-click>
```py {none|1|1-2}
print('hello, world')
print('goodbye, world')
```
</v-click>

<br>

<v-click>
```cmd
python C:\code\ex01.py
```
</v-click>

<br>

<v-click>
```cmd
python3 /Users/Sang/ex01.py
```
</v-click>


---
level: 2
transition: fade-out
---

# Comments

<v-click>

```py {7|1-6|all}
"""
The first program - hello, world

Version: 1.0
Author: Sang
"""
# print('hello, world')
print("Xin Chao The Gioi！")
```

</v-click>


---
transition: fade-out
# apply any unocss classes to the current slide
class: text-center py-50 font-bold
---

# Variables
