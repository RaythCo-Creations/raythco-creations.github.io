---
title: "Non-Minecraft - Downloads"
layout: downloads
permalink: /downloads/other
---

On this page you can find a list of all the available non-minecraft downloads on this website. Please refer to the list below.

{% for item in site.data.downloads.other %}

### [{{ item.title }}]({{ item.url }})

{{ item.description }}

****************
{% endfor %}
