---
layout: page
title: "10 Days"
excerpt: "Countdown to Mankind's Giant Leap"
modified: 2019-07-12T19:44:38.564948-04:00

---


| Project | Description | Link |
|---|---|---|
{% for post in site.categories.days10 %}
   | {{ post.title }} | {{ post.excerpt }} | <a href="{{ site.url }}{{ post.url }}"> link </a>   |
{% endfor %} 
