[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# About
You are welcome to:
- play with the [demo](https://markdownit.salalex.repl.co),
- examine the code [in this REPL](https://repl.it/@salalex/markdownit).

This project is a humble example/experiment on how to integrate different markup syntax parsing in frontend, including following:
- [markdown](https://en.wikipedia.org/wiki/Markdown) via [markdown-it.js](https://github.com/markdown-it/markdown-it),
- [mediawiki](https://www.mediawiki.org/wiki/Help:Formatting) via [wiki2html.js](https://remysharp.com/downloads/wiki2html.js)

Other external libraries and resources used in this project:
- css by [github-markdown-css](https://github.com/sindresorhus/github-markdown-css)
- icons by [icons8.com](https://icons8.com/icon/new-icons/material-outlined)
- [Wikipedia logo](https://commons.wikimedia.org/wiki/File:Wikipedia-logo.png)

# Further ideas

## Frontend Plugins
- frontend plugin to display/generate table of contents (TOC)
- frontend plugin to crawl and index all linked local pages for following purposes:
  - display directory of pages,
  - enable freetext/keyword search,
  - display/generate tag cloud.

## Backend Plugins
- backend plugin to list files and subdirectories within local directory (optionally matching specified pattern)
- integrate an editor, like [SimpleMDE](https://simplemde.com) ([GitHub](https://https://github.com/sparksuite/simplemde-markdown-editor))

(text below is an example of markdown syntax for test purposes only)

----

# Example 1
Links
- [Wikipedia](https://en.wikipedia.org/wiki/Main_Page)
- [example2](example2.md)
- [example3](./test_folder/example3.md)
- [Mediawiki](./test_folder/document.mediawiki)

# markdown-it rulezz!
[github.com/markdown-it](https://github.com/markdown-it/linkify-it)

# Wikipedia Logo

## Local file (in subdirectory)
![Wikipedia Logo - Local](./test_folder/Wikipedia-logo.png 'Wikipedia')

## External URL
![Wiki Logo External](https://upload.wikimedia.org/wikipedia/commons/6/63/Wikipedia-logo.png 'Wiki Logo External')
