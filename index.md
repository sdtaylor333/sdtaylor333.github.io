---
layout: default
title: Home
---

# Salvation and the Risen King

Essays exploring union with Christ, the kingdom of God, and faith as allegiance to the risen King.

These essays develop themes from my forthcoming book *[Salvation and the Risen King](/books)*.

<p align="center">
<a href="/books">
<img src="/salvation-risen-king-cover-v2.jpg.png" width="220">
</a>
</p>

## Essays

{% for post in site.posts %}

### [{{ post.title }}]({{ post.url }})

{{ post.date | date: "%B %d, %Y" }}

{% endfor %}
