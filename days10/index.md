---
layout: page
title: "10 Days"
excerpt: "Countdown to Mankind's Giant Leap"
modified: 2019-07-12T19:44:38.564948-04:00

---


| Project | Description |
|---|---|
{% for post in site.categories.days10 %}
|<a href="{{ site.url }}{{ post.url }}"> {{ post.title }} </a> | {{ post.excerpt }} |
{% endfor %}
