---
layout: page
show_meta: false
title: "Technology"
subheadline: ""
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/technology/"
---
<ul>
    {% for post in site.categories.technology %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>