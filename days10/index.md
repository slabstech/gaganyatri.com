---
layout: page
title: "10 Days"
excerpt: "Countdown to Mankind's Giant Leap"
modified: 2019-07-12T19:44:38.564948-04:00

---


Ver 2
{% for post in site.categories.days10_2 %}
|<a href="{{ site.url }}{{ post.url }}"> {{ post.title }} </a> | {{ post.excerpt  | markdownify | strip_html | strip_newlines | escape_once }} |
{% endfor %}


Ver 1
{% for post in site.categories.days10 %}
|<a href="{{ site.url }}{{ post.url }}"> {{ post.title }} </a> | {{ post.excerpt  | markdownify | strip_html | strip_newlines | escape_once }} |
{% endfor %}
