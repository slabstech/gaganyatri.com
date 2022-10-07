---
layout: page
title: "Open Space"
excerpt: "Collision of Ideas"
modified: 2022-10-06T19:44:38.564948-04:00

---

* House Rules
  * Membership via Invite Only
  * Membership annulled, if 3 consecutive meets are skipped
  * No membership fees
  * Non-alcoholic, smoke-free and meatless sessions
  * Bring your food/ beverages/ order nearby
  * Host - gets a veto on barring members from a single meet
  * Location - Voluntary hosting by members based on available space for members
  * Group size - 10 
    * Add +1 members, by presenting 3 topics
    * Members added to wait-list, become members once next pingala sequence is reached
    

<ul class="post-list">
{% for post in site.categories.openspace %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} : {% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %} :  <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span> </a></article></li>
{% endfor %}
</ul>
