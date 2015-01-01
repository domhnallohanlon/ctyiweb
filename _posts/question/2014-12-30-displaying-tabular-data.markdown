---
layout: question
title:  "How do I display tabular data?"
date:   2014-12-30 13:37:00
thumb: 75.png
author: Domhnall
categories:
- question
- html
- tables
---

### Overview
Back in the day of HTML4 developers used tables to layout their entire sites. This lead to lots of hard-to-read, nested code and layouts that left a lot to be desired. While this practice has largely stopped tables are still very useful for their original purpose - displaying tabular data.
<!--more-->

####<table>

To create a table you need a pair of opening and closing table tags like so; `<table> </table>` different browsers will display tables in different ways so it is a good idea to specify what properties you want. Here's an example with some inline CSS, but remember you should usually keep your styles in a seperate stylesheet.
`<table style="margin: 2px solid black"> Table Contets </table>`
<table style="margin: 2px solid black"> 
    Table Contets 
</table>

####<tr>
If you're familiar with spreadsheets, such as Microsoft Excel or Google Sheets, you'll know already that data tables are made up of rows and columns. In HTML you start by creating the number of rows you want and then divide those rows up into seperate columns. Lets look at this in more detail. <table>

    <table style="margin: 2px solid black">
        <tr>Top Row</tr>
        <tr>Bottom Row</tr>        
    </table>

Creates a table that looks like this:

<table style="margin: 2px solid black">
    <tr>Top Row</tr>
    <tr>Bottom Row</tr>        
</table>

####<td>
colspan

####<th>

#### the other one

#### dummy data.