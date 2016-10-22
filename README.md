# Doc42

> Doc42 is a Jekyll and Kissui starter kit to create awesome documentations.

Kissui + Markdown = :rocket:

<center><img src="http://doc42.io/images/b1.png" /></center>

# Installation

Before you start, make sure you have Jekyll installed. Read [here](http://jekyllrb.com/docs/installation/) for a quick installtion.

After installing Jekyll, clone or download this repo, open Terminal, `cd` to the `doc42` folder and run:

```
jekyll server
```

*Note: it's better to clone this repo instead of download the content. This way, you can always update the repo with a `git pull` command.*

# Adding, updating and removing docs

All documentation pages go under the `/docs` folder. Create folders under the `/docs` and put pages there:

Example:

```
/docs
   |- basics
        |- elements.html
   |- applications
        |- helloworld.html
   |- faq
        |- index.html
```

Each page can define this parameters:

- layout
- title
- categories
- permalink

Example: 

```
layout: doc
title: Typography
categories: basics
permalink: /docs/basics/typography/
```


# Details

### What is Kissui?

[Kissui](http://kissui.io) is a web development kit. It has a lot of fancy features to create an awesome web app. 

### What is Jekyll?

> Transform your plain text into static websites and blogs.

[Jekyll](http://jekyllrb.com/) is a platform to convert Markdown to HTML. It doesn't have any database and stores all data on a Git repo. 

### What `doc42` means? 
`Doc` means documentations and `42` is the answer to everything. Read more [here](https://duckduckgo.com/?q=Answer+to+the+Ultimate+Question+of+Life%2C+the+Universe%2C+and+Everything).


# Author
Afshin Mehrabani

# License
MIT
