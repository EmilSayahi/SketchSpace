# SketchSpace
The space for your comics on the web.
<center><img src="https://github.com/EmilSayahi/SketchSpace/raw/master/img/logo_cropped.png"></img></center>

This site is built on [Garrett Boatman's blank Jekyll template](https://github.com/garrettboatman/Blank-Theme-Jekyll) and [Lài Xìntāo's Jekyll stylesheet.](https://github.com/laixintao/Princess-Diaries/tree/master/_sass)

[Demonstration](http://emilsayahi.github.io/SketchSpace)


<center><img src="https://github.com/EmilSayahi/SketchSpace/raw/master/img/example_screenshot.PNG"></img></center>


## Setup
1. Personalize the ```_config.yml``` file in your installation directory.
2. Begin uploading your posts to the ```/_posts``` directory of your installation.

This is assuming that you have hosting in place.
You can self-host Jekyll and then supply this repository to the Jekyll software on your server, or you can host on [GitHub Pages](https://pages.github.com/).

## Posting comics
All posts on SketchSpace must follow the following format:

```

---
title: Comic Title
date: YYYY-MM-DD HH:MM:SS -HH:MM
layout: comic
---

{% include comic.html comic="http://example.com/comics/example-comic.jpg" %}

```

Important note: Jekyll seems to have issues with compiling a post if the comic path is a URN instead of a URL, so give absolute paths instead of relative ones.


Save your post as a .markdown file, with the filename containing just ANSI characters with no spaces into the ```_posts``` directory of your installation. If you need spaces, replace them with dashes or underscores. The name must begin with the date in the following format:


```YYYY-MM-DD```

Save your comics themselves as images in the ```comics``` directory of your installation. These are what go into your .markdown files.
