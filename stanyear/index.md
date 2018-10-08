---
layout: page
title: Years For Stanford "Stanford Dream"
excerpt: "Why, How and When for Stanford"
search_omit: true
---

The preparation, motivation and possible journey for [Stanford](https://www.stanford.edu) 


<ul class="post-list">
{% for post in site.categories.stanyear %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>
