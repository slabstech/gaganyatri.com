---
layout: page
title: Nimbro
excerpt: Open Humanoid Platform developed at AIS, Uni-Bonn
search_omit: true
---

Brief overview of the Nimbro-OP platform over the years . [source](http://nimbro.net)




<ul class="post-list">
{% for post in site.categories.nimbro %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>
