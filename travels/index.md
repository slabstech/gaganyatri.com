---
layout: page
title: "ಅಲೆಮಾರಿ / Wandern"
excerpt: "A way into the world"
---

Travel's now exclusively maintained at [ಅಲೆಮಾರಿ / alemaari.in](https://slabstech.com/alemaari.in)

<ul class="post-list">
{% for post in site.categories.travels %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} : {% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %} :  <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span> </a></article></li>
{% endfor %}
</ul>
