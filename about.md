---
layout: page
title: About
permalink: about
---

This is a jekyll theme created using the css library [bulma](http://bulma.io).
This theme is created as an lightweight and minimalistic blog theme for free use.  

**Important things to note if you decide to use this setup**  
A post can have a post photo, which means that the photo is displayed on the home page,
too achieve this, please insert the image in the images folder in assets, and insert the
name of the file with the post information.  
This is done by creating a variable **picture** at the top of your markdowns front matter.

```
    picture: imagename.jpg
```

Your front matter should look something like this:

```
    ---
    layout: post
    title:  "Welcome to Jekyll!"
    date:   2017-03-26 13:15:59 +0200
    author: LitenApe
    picture: post-photo.jpg
    categories: post
    ---
```

The variable picture should not be present if you do not have a post picture.  

All new posts should be saved inside the \_posts directory in the format:  
```
    YYYY-MM-DD-name-of-post.md
    or
    YYYY-MM-DD-name-of-post.markdown
```

If you desire any colour changes, please add the new rules inside the **jekyllxbulma.css** file.
Or if possible, change the already existing rules, I would not recommend to under any circumstances
to modify the **bulma.css** file, because of it's size.  

If you want to deplay the blog with github pages, please take a look at the
[jekyll documentation](http://jekyllrb.com/docs/github-pages/) for a step by step
guide on how to deplay the blog using github-pages

**Final notes**  
As you probably know by now, the theme is created with the help of bulma,
I changed as little of the default styling as possible, but tried to make
the theme as blogging friendly as possible. If you want to make this theme
better, please contribute by sending a PR or an mail explaining to me what
can be done to improve it.  
The blog title should be changed to the desired name by changing the value
of the **title** variable inside the **_config.yml** file
