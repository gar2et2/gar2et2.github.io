---
layout: page
show_meta: false
title: "Digital"
subheadline: ""
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/digital/"
---
<ul>
    {% for post in site.categories.digital %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>