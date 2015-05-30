---
layout: page
show_meta: false
title: "Random"
subheadline: ""
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/random/"
---
<ul>
    {% for post in site.categories.random %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>