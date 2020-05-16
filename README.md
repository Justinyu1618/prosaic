# Personal Website

Custom jekyll theme I made for my personal website. 


## Installation
Make sure to have jekyll installed. Then, navigate to the directory and run:
```
bundle exec jekyll serve
```

The website will be running at `http://127.0.0.1:4000/`.


## Projects
This jekyll theme makes it easy to display projects in a card format. To add a new project, create a new file in `_projects` with format `YEAR-MONTH-DAY-title.md` 

**Example:**
```
---
title: Distributed Deep Learning on the Blockchain + the Cloud
description: Super top secret project
cover: /assets/images/project.png
key: appreader                                  # unique key for project 
github: https://www.github.com                  # optional 
demo: https://www.google.com                   # optional 
---
This is my project description for my super top secret project.

The description can be written in (kramdown)[https://kramdown.gettalong.org/]

![woah images are cool](/assets/images/example.png){:class="project-img"}
```


This jekyll theme is loosely based on [Minimalist](https://github.com/Trybnetic/minimalist)