---
layout: page
title: "Dark: Light"
excerpt: "In Pursuit of Happiness"
---
<ul class="post-list">
{% for post in site.categories.dark_light %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} : {% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %} :  <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span> </a></article></li>
{% endfor %}
</ul>


You only live once 

Do u live like it's your last day, or do u disappear like everyone else