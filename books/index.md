---
layout: page
title: Books
excerpt: "Collections of published books"
search_omit: true
---

<ul class="post-list">
{% for post in site.categories.books-pub %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>



<br/>
<h1>
  <a href="https://amzn.to/2PUILxX">
    Buy the Book :
    <u> Why </u>
  </a>
</h1>
<br/>
