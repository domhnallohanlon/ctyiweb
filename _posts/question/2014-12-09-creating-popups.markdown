---
layout: question
title:  "How do I create pop-up boxes?"
date:   2014-12-09 13:37:00
author: Domhnall
categories:
- question
- javascript
- alert
- prompt
---

### Overview

There are often times when you want to either give your user some output, or take some input from them. In either 
case we should hopefully be able to answer both these questions with javascript below.

#### Alert

TODO: make an in-line call first then do this bit

The built-in alert() function simply displays a message in a dialog box to the visitor. One way to create 
it is as follows:
    
    function popUp(){
      alert("Hello World");
    }
    
We have now created our own `popUp()` function that can be called by any element within our HTML that accepts 
an `onclick()` attribute, such as a button.button

    <button onclick=(popUp)>Click Me </button> 

This button will now trigger an alert box any time it is clicked.


**Browser Support**:

#### Prompt

**Browser Support**
