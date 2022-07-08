---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

(getting_started)=


# Setting up Your JavaScript Environment

## Overview

In this lecture, you will learn how to

1.  get a JavaScript environment up and running
2.  execute simple JavaScript commands
3.  run a sample program


## node.js

We will start by installing node.js in your computer if not yet installed. Please note initially you will not need it but will work with it intensively as the
tutorial builds on.

The following [node.js](https://nodejs.org/) is the site which one can find the downloads files which we would then use for installing node.

```{figure} /_static/lecture_specific/getting_started/node_installation.png
:scale: 60%
:name: node_installation

A node.js download window viewed in the browser
```

```{note}
All of what follows assumes that you adopt this recommendation!
```

(install_node)=

### Installing node

To install node, [download](https://nodejs.org/en/download) the
binary and follow the instructions.

Important points:

-   Install the latest version!

```{figure} /_static/lecture_specific/getting_started/node_install.png
:scale: 60%
:name: node_install

You should be able to get something similar to the picture above when installing
```

### Checking Version & Updating node

node supplies a tool called `npm` that can be used to
upgrade your node.

```{note}
npm consists mainly of two things. One, it is an online repository for the publishing of open-source Node. js projects; 
Lastly, it is a command-line utility for interacting with the said repository and aids in package installation, version management, and dependency management.
```

As a practice run, please execute the following

1.  Open up a terminal
2.  Type `node -v ` (to check the node version).
3.  Type `npm install npm@latest -g` (This would have npm install the latest node as a package)

For more help on `npm`, type `npm help` in a terminal.


## Browser

Next you have to install a browser if you do not already have it on your computer. There are many types of browsers around but I strongly recommend that you download and use Google chrome; if you using a different type.


### Installing Chrome

To install chrome visit the following link - [Google Chrome](https://www.google.com/chrome/)

```{note}
It is here where we will write small JavaScript code on the "browser console", but we do not use the browser console to develop the applications themselves.

```

```{figure} /_static/lecture_specific/getting_started/google_install.png
:scale: 60%
:name: google_install

You should be able to get something similar to the picture above when downloading and installing
```

### Starting Chrome

Once you have installed Chrome, you can start it:

Either by

-   Search for Chrome in your applications menu, or
-   Click on the chrome menu either on start-up menu or desktop if using Windows

Hopefully, your browser will open up with a web page that
looks something like this

```{figure} /_static/lecture_specific/getting_started/google_browser.png
:scale: 60%
```

### Opening Google Chrome Console

Once Chrome is open, you can open the console by:

Either by
     
-  Clicking the three dots at the top right corner of the browser, 
-  selecting More tools -> Developer tools
-  using a keyboard shortcut(ctrl + shift + i or F12)when using windows.


```{figure} /_static/lecture_specific/getting_started/google_console.png
:scale: 60%
:name: google_console

You should get something similar to the picture above when the console is open.
```

Next after opening the Google Chrome console, try to explore the different buttons. We will spend a considerable amount of time on the Console. 

This is the place where your JavaScript code goes. The Google Console V8 engine changes your JavaScript code to machine code.

To get a grasp let us write code on the console:

#### Writing Code on Browser Console

Next we will do a quick how to, edit code and run simple programs on Chrome.

```{note}
We can write any JavaScript code on the Google console or any browser console. However, for this challenge, we only focus on Google Chrome console. Open the console using:
```


### Code Editor

### Console.log

The console.log is a built in function in chrome that we will use to write our code. Let us start by passing an argument as input data. 

The function will then display the given argument "Hello, World".

```
console.log('Hello, World!')
```

Below is a screenshot of the console.log function in play.

```{figure} /_static/lecture_specific/getting_started/console_log.png
:scale: 60%

```