---
layout: page
title: Research
excerpt: "Research Projects"
search_omit: true
---

### Publications

1. Trace Transform based identifier for speech based image retreival in Mobile phones. [link](http://ieeexplore.ieee.org/document/6637307/)
2.  Special Pedestrian and Head Pose Detection for Autonomous Vehicles.
[ToBePublished](sachinsshetty.github.io)
3. Special Pedestrian Detection and Head Pose Detection for Autonomous Vehicles Using Ensemble Learning [ToBePublished](sachinsshetty.github.io)
4. Digital Heritage Conservation through Image Classification and 3D reconstruction. [ToBePublished](sachinsshetty.github.io)

<ul class="post-list">
{% for post in site.categories.research %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>
