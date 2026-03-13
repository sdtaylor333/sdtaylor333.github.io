---
layout: default
title: Home
---

# Essays on Salvation, Union with Christ, and the Kingdom of God

These essays explore themes from my forthcoming book *[Salvation and the Risen King](/books)*.

<p align="center">
<a href="/books">
<img src="/salvation-risen-king-cover-v2.jpg.png" width="220">
</a>
</p>

## Essays

<ul>
{% for post in site.posts %}
  <li>
    {{ post.date | date: "%B %-d, %Y" }} – 
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
