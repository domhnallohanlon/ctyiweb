---
layout: question
title:  "How do I style text?"
date:   2014-12-05 13:37:00
thumb: 75.png
author: Domhnall
categories:
- question
- html
- css
- text
---

### Overview

Previously we've seen how to display blocks of text on a page, and how to choose the font for those blocks of text. The last thing we want to do is style individual words or sentences on the page. This might be an aesthetic decision, like using drop caps or small caps at the beginning of a new paragraph. Alternatively, it could be to add emphasis to particular words or sentences by using bold, italic or underlined text. Certain pieces of text can also be styled to reflect the fact that updates or changes have been made to the page by using the strikethrough tag.
<!--more-->

<br><br>

#### Bold Text
<span class="fa-stack fa-lg">
  <i class="fa fa-square fa-stack-2x"></i>
  <i class="fa fa-bold fa-stack-1x fa-inverse"></i>
</span><br>

You can make text bold be using the `<b>` tags (for bold) or `<strong>` tag.
As an example, take the following block of code:
    
    <b>This text is emboldened with <b> tags </b>
    <strong> This text is emboldened with <strong> tags</strong>

Which gets rendered like so:<br>

<b> This text is emboldened with &lt;b&gt; tags </b> <br>
<strong> This text is emboldened with &lt;strong&gt; tags </strong>
<br><br>
**Browser Support**:

<br><br>

#### Italic Text
<span class="fa-stack fa-lg">
  <i class="fa fa-square fa-stack-2x"></i>
  <i class="fa fa-italic fa-stack-1x fa-inverse"></i>
</span><br>
You can make text italic using `<i>` tags or `<em>` tags (for emphasis).

Take for example this code snippet:
    
    <i>This text is italicised with <i> tags</i> <br>
    <em>This text is italicised with <em> tags</em>

<br>

Which is rendered by your browser as:<br>
<i> This text is italicised with &lt;i&gt; tags </i> <br>
<em> This text is italicised with &lt;em&gt; tags </em>
<br><br>
**Browser Support**

<br><br>

#### Underlined Text
<span class="fa-stack fa-lg">
  <i class="fa fa-square fa-stack-2x"></i>
  <i class="fa fa-underline fa-stack-1x fa-inverse"></i>
</span><br>
You can create underlined text but using a `<u>`.

Here's a quick example:

    <u>This text is underlined using <u> tags. </u>

Which displays as: <br>
<u>This text is underlined using &lt;u&gt; tags. </u>
<br><br>
**Broswer Support**

<br><br>

#### Strikethrough

<span class="fa-stack fa-lg">
  <i class="fa fa-square fa-stack-2x"></i>
  <i class="fa fa-strikethrough fa-stack-1x fa-inverse"></i>
</span><br>
To create strikethrough text use `<s>` tags or `<del>` tags. In HTML 4 you could also use the `<strike>` tag but it is no longer used in HTML 5. Here's an example of these tags in use:

    <p>
        This is what the <s> tag looks like <s>in action</s> <br>
        This is what the <del> tag looks like <del>in action</del> <br>
        This is what the <strike> tag looks like <strike> in action</strike> 
    </p> 
<br>
This code is rendered like so:
<p>
    This is what the &lt;s&gt; tag looks like <s>in action</s> <br>
    This is what the &lt;del&gt; tag looks like <del>in action</del> <br>
    This is what the &lt;strike&gt; tag looks like <strike> in action</strike> 
</p> 

**Browser Support**

<br><br>

#### Small Caps
Small caps should be used sparingly - typically you might see them at the begining of a new chapter in a book or for a new entry in a dictionary or encyclopaedia. Small Caps do not have their own HTML tag, rather they need to be styled using using the CSS `font-variant` property. Take for example the following block of code:
    
    <p style="font-variant:small-caps">
    This text is rendered as small caps
    </p>

which would be displayed in a browser like so:

<p style="font-variant:small-caps">
This text is rendered as small caps
</p>
The other acceptable values for the `font-variant` property are:
-`normal`
-`small-caps`
-`initial`
-`inherit`
<br><br>
**Browser Support**
<br><br>

#### text-transform

This is another CSS property that is useful to know if you need to style a lot of text. Here are three examples to demonstrate its use:

    <p style="text-transform:uppercase">
        This text will all be displayed as uppercase
    </p>
    <p style="text-transform:lowercase">
        THIS text will all be displayed as LOWERCASE
    </p>
    <p style="text-transform:capitalize">
        The first letter of every word will be capitalised
    </p>

And they will be displayed on a webpage as:

<p style="text-transform:uppercase">
    This text will all be displayed as uppercase
</p>
<p style="text-transform:lowercase">
    THIS text will all be displayed as LOWERCASE
</p>
<p style="text-transform:capitalize">
    The first letter of every word will be capitalised
</p>

<br><br>
**Browser Support**
