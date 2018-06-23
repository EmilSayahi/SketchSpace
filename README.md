# SketchSpace
The space for your comics on the web.


This site is built on [Garrett Boatman's blank Jekyll template.](https://github.com/garrettboatman/Blank-Theme-Jekyll)

[Demo](http://emilsayahi.github.io/SketchSpace)




## Setup
1. Personalize the config.yml file in your installation directory.
2. Begin uploading your posts to the /posts/ directory of your installation.

This is assuming that you have hosting in place.
You can self-host Jekyll and then supply this repository to the Jekyll software on your server, or you can host on [GitHub Pages](https://pages.github.com/).

## Posting comics
All posts on SketchSpace must follow the following format:

```

---
title: Comic Title
date: YYYY-MM-DD HH:MM:SS -HH:MM
categories:
- categories_are_optional
layout: comic
---

{% include image.html image="/comics/example-comic.jpg" %}

```
