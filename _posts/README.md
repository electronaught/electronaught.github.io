# Adding blogposts to your site

Simply create a markdown file for each post you want to create, and follow the naming convention:

`YYY-MM-DD-Post-Name.md`

Inside of the markdown file, be sure to include the following information at the very top:

```
---
layout: post
title: "EN#1 - Digital Synthesiser (Introduction)"
date: 1972-01-01
---
```

* the `layout` field tells Jekyll which layout file to use when formatting your markdown content (hint: this example will use `post.html`)

* the `title` field is used to name your post.  This is what will appear in the <h1> header at the top of the blog page.

* the `date` field is used to sort and define the page address for this post.