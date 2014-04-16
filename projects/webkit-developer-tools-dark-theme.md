---
title: Webkit Developer Tools Dark Theme
permalink: webkit-developer-tools-dark-theme
description: Dark theme for Chrome Developer Tools
homepage: 
languages: []
visible: false
order: 
# Github Flavored Markdown reference
# https://help.github.com/articles/github-flavored-markdown
---


webkit-developer-tools-dark-theme
=================================

Obsidian Dark theme for Chrome Developer Tools

### How to install Obsidian theme into Chrome

Copy Custom.css into:

* Mac OSX 

```
  ~/Library/Application Support/Google/Chrome/Profile 1/User StyleSheets/Custom.css
```
* Windows 

```
  %USERPROFILE%\AppData\Local\Google\Chrome\User Data\Default\User StyleSheets\Custom.css
```
* Ubuntu 

```
  ~/.config/chromium/Default/User StyleSheets/Custom.css
```


### Build

* Download & install [NodeJS](http://nodejs.org/download/)
* Install Stylus

```
  npm install stylus -g
```
* Compile to css

```sh
  stylus < Custom.styl > path/to/Custom.css
```
