---
title: Our Drama Museum
layout: index
---

{% for exhibit in site.exhibits %}

<img src="{{ exhibit.image-url }}" width = 256>
<p><a href="{{ exhibit.drama-url }}">{{ exhibit.title }}</a> by {{ exhibit.writer }}</p>
<p>{{ exhibit.short-introduction }}</p>

{% endfor %}