---
title: "GitHub Pages with Jekyll"
date: 2023-03-09
tags: github jekyll web
---
Quick notes from following the GitHub Pages tutorial.

Apparently Pages defaults to Jekyll, so we don't even need to point to that in the repo! It all starts from the repository Settings tab. From there, pages can be activated. Just point it to the master/main/production branch that you want built, and hit save.

_config.yml in the root directory is used for Jekyll configuration. Here are a few properties:  
theme: name of a jekyll theme. My immediate thought is how can I point this to something in the repo instead?  
title: name of the site. Also this is a property per-page. Does that mean pages can be themed within a container of the main theme?  
description: description of the site.  

index.md becomes the homepage, or readme.md if the index isn't present.

All fascinating stuff. Let's move on.

This here is a "blog post", but I wonder if it's how all Jekyll pages work. This post is created by adding a markdown file in the \_posts folder, with a name like "YYYY-MM-DD-title.md" then they have the gall to tell you to write the date and title _again_ in Frontmatter. Then you can add markdown to your hearts content.

Time to RTFM.
[Useful Jekyll Docs](https://jekyllrb.com/docs/posts/)

