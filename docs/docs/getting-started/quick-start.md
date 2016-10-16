---
layout: doc
title: Quick Start
categories: getting-started
permalink: /docs/getting-started/start
---

In this section we study how to install dependencies and how to create the first Doc42 page.

### Installation

Before you start, make sure you have Jekyll installed. Read [here](/docs/getting-started/installing-jekyll) for a quick installtion.

After installing Jekyll, clone or download this repo, open Terminal, `cd` to the `doc42` folder and run:

```
jekyll server
```

*Note: it's better to clone this repo instead of download the content. This way, you can always update the repo with a `git pull` command.*

### Adding, updating and removing docs

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

Read more about page's properties [here](/docs/basics/pages)
