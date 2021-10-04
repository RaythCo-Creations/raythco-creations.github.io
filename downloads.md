---
title: Downloads
layout: downloads
order: 3
---
This is my downloads page. Below you will see a table with the various categories for downloads.

## Download Categories

{% for item in site.data.nav.dlpages %}
<h3><a href="{{ item.url }}">{{ item.title }}</a></h3>
****************
{% endfor %}
