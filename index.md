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

{% for post in site.posts limit:3 %}

### [{{ post.title }}]({{ post.url }})

<p style="margin-top:-8px; color:#666;">
{{ post.date | date: "%B %-d, %Y" }}
</p>

<hr style="margin:30px 0;">

{% endfor %}

<p><a href="/essays">View all essays →</a></p>
