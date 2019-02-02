---
layout: page
title: Rally For Rivers
excerpt: Rejuvenating Rivers
search_omit: true
---

Insights from movement
### Rally For Rivers

Read more at [link](https://isha.sadhguru.org/rally-for-rivers/)

Interpretation of the draft policy : [download](https://cdn.isha.ws/public/docs/pdir/RFR_RevitalizationOfRiversInIndia-Web.pdf)


<ul class="post-list">
{% for post in site.categories.rivers %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>
