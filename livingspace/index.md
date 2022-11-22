---
layout: page
title: "Living Space"
excerpt: "Collision of Ideas"
modified: 2022-10-06T19:44:38.564948-04:00

---

3 Month Target  - 21/11/22 To 20/2/24
1. Prototype for "Bhoomi : Garuda" module 
2. 1 Patent Application Completion
3. 1 Conference Full paper submission 


Garuda module
1. Orientation - Navigation- Sachin
2. Vision: Plant identification- Rohith
3. DNA algorithm- snapshots - TBD 
4. Scheduler - TBD 
5. Raspberry Pi Deployment- TBD
6. MuJoCo Simulation- TBD


 ---
Your goal, should be the reason to jump out of of bed every morning. 

Ikigai should be definite, audacious, never been done before, for glory only comes to those
Who eat impossible for breakfast 

Times flies away, if one doesn't utilize it immediately and intelligently with direction.

Your goal, should be the reason to jump out of of bed every morning. 

Ikigai should be definite, audacious, never been done before, for glory only comes to those
Who eat impossible for breakfast 

Times flies away, if one doesn't utilize it immediately and intelligently with direction.

Only one priority,  build a 1000 years Mars civilization.  Everything else is a distraction and should be rejection immediately Your goal, should be the reason to jump out of of bed every morning. 

Ikigai should be definite, audacious, never been done before, for glory only comes to those
Who eat impossible for breakfast 

Times flies away, if one doesn't utilize it immediately and intelligently with direction.

Your goal, should be the reason to jump out of of bed every morning. 

Ikigai should be definite, audacious, never been done before, for glory only comes to those
Who eat impossible for breakfast 

Times flies away, if one doesn't utilize it immediately and intelligently with direction.

Only one priority,  build a 1000 years Mars civilization.  Everything else is a distraction and should be rejection immediately 

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
{% for post in site.categories.livingspace %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} : {% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %} :  <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span> </a></article></li>
{% endfor %}
</ul>
