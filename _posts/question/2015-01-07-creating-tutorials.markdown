---
layout: question
title:  "How do I write helpful tutorials?"
date:   2015-01-07 13:37:00
thumb: 75.png
author: Domhnall
categories:
- question
- html
- instructions
---

### Overview
The single best thing about the internet is the sheer volume of information that it has made available to ordinary people for free. If you figure out something cool and want to share it online then do. Here are a few pointers to help make your technology tutorials a little bit easier to read...
<!--more-->

#### Where's the "Any" key?

If you want to typeset a keyboard short cut then don't just type it in some old `<p>` tag, use the keyboard tag: 

    <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Del</kbd>

Will output <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Del</kbd>


#### Code

There are lots of ways to display code on screen, the simplest is using the code tag:

    <code>
        <html>
        <head>
            <title></title>
        </head>
        <body>
            <p>
                Contents goes here
            </p>    
        </body>
        </html>
    </code>

<br> Which will produce something like the following: <br><br>
`<html>`<br>
`<head>`<br>
&emsp;    `<title></title>`<br>
`</head>`<br>
`<body>`<br>
&emsp;    `<p>`<br>
&emsp;&emsp; Contents goes here <br>
&emsp;    `</p>`<br>
`</body>`<br>
`</html>` <br>
<br>
I've added in some spacing using escape characters so that it displays similarly to how it would in a text editor.