---
layout: page
title: Comics
permalink: /comics/
---
 {% for comic in site.comics %}

### <img src='../images/icon_reddit.svg' width="40px" height="40px"> **[{{ comic.name }}]({{ comic.webpage }})** <img src='../images/icon_reddit.svg' width="40px" height="40px">

<img src='{{ comic.image_url }}'>

 {% endfor %}