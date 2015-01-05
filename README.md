##README.md
============

### Overview

At the moment there are only 5 types of pages on the site. 

1. There are overview pages, such as html.html or css.html that contain an overview specific topics. These are all contained in the root directory. All other types of pages are contained in the **_posts** folder.
2. There are blog posts, which are intended to shed some insight into the learning process and for sharing resources. 
3. Projects are intended to be short to medium sized activities for students to apply what they have learned about web development. In an ideal world these projects would be categorised based on the amount to prior knowledge needed to obtain a MWE.
4. Questions make up the bulk of the site. The are intended to introduce students to individual topics, with code snippets and potential pitfalls where applicable. 
5. Software posts are articles about different types of software that can be used for web development. Software posts have the category "softwares"



###Customize  
Most general settings and data like site name, colors, address, etc. can be configured and changed right in the main config file: `/_config.yml`
The main colours are "primary" and "secondary"


The content of the Home page can be changed here: `/home.html`
The content of the About page can be changed here: `/about.html`
The content of the HTML page can be changed here:`/html.html`
The content of the CSS page can be changed here:`/css.html`
The content of the Javascript page can be changed here:`/javascript.html`
The content of the Software page can be changed here:`/software.html`

In the event of a broken link double check that the path begins with /ctyiweb/

####Blog post
Create a Blog post by creating a file called `yyyy-mm-dd-name-of-post-like-this.markdown` in the `/_posts/blog/` directory with the following template:
```markdown
---
layout: post          #important: needs to be type post
title: "Name of post like this"
date: yyyy-mm-dd hh:mm:ss
author: Name
categories:
- blog                  #important: leave "blog" first
- category1             #don't forget the space after the hypehens!
- category2
- ...
img: post01.jpg       #place image (850x450) with this name in /assets/img/blog/
thumb: thumb01.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---
This text will appear in the excerpt "post preview" on the Blog page that lists all the posts.
<!--more-->
This text will not be shown in the excerpt because it is after the excerpt separator.
```
####Project post
Create a Project post to go in your Portfolio by creating a file called `yyyy-mm-dd-name-of-the-project.markdown` in the `/_posts/project/` directory with the following template:
```markdown
---
layout: project       #important: don't change this
title:  "Name of the project"
date: yyyy-mm-dd hh:mm:ss
author: Name
categories:
- project             #important: leave this here
img: portfolio_10.jpg #place image (600x450) with this name in /assets/img/project/
thumb: thumb02.jpg
carousel:
- single01.jpg        #place image (1280x600) with this name in /assets/img/project/carousel/
- single02.jpg  
- ...
client: Company XY
website: http://www.internet.com
---
####This is a heading
This is a regular paragraph. Write as much as you like.
```


####Software Post
Create a Software post (that is listed in the Software section on the Home page) in this directory by creating a file called `yyyy-mm-dd-name-of-software.markdown` in the `/_posts/software/` directory with the following template:
```markdown
---
layout: software
title:  "Yet Another Text Editor"
date: yyyy-mm-dd hh:mm:ss
author: First Last
categories:
- softwares       #note: softwares rather than software
- first category
- another category
---
####About the editor
Some intro info goes here
<!--more -->
Anything below the excerpt seperator gets ignored on the preview page.
```

####Question Post
Create a Question entry (that is listed in the Frequently Asked section on the Home page) in this directory by creating a file called `yyyy-mm-dd-do-i-have-a-question.markdown` in the `/_posts/project/` directory with the following template:
```markdown
---
layout: question
title:  "Do I have a question?"
date: yyyy-mm-dd hh:mm:ss
author: First Last
categories:
- question       #important: leave question here, add other categories below
- first category
- another category
---
####Can I Borrow a Feeling?
Can you lend me a jar of love?
```

####Publish
To publish with [GitHub Pages](https://pages.github.com/), simply create a branch called `gh-pages`in your repository. GitHub will build your site automatically and publish it at `http://yourusername.github.io/repositoryname/`.  
If there are problems with loading assets like CSS files and images, make sure that the `baseurl` in the `_config.yml`is set correctly (it should say `/repositoryname`).

If you want to host your website somewhere else than GitHub (or just would like to customize and build your site locally), please check out the [Jekyll documentation](http://jekyllrb.com/). 

###Credits
This is a [Jekyll](http://jekyllrb.com/) port of the [Solid theme](http://www.blacktie.co/2014/05/solid-multipurpose-theme/) by [blacktie.co](http://www.blacktie.co/). Visit the [live demo](https://st4ple.github.io/solid-jekyll/) for a preview. 

###Usage
This theme can be customized, built and published straight from GitHub, thanks to [GitHub Pages](https://pages.github.com/). A local installation of Jekyll isn't even necessary!

[Fork this repository](https://github.com/st4ple/solid-jekyll/fork) to get started. 
