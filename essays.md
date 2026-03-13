---
layout: default
title: Essays
---

## Essays

{% for post in site.posts %}

### [{{ post.title }}]({{ post.url }})

<p style="margin-top:-8px; color:#666;">
{{ post.date | date: "%B %-d, %Y" }}
</p>

<hr style="margin:30px 0;">

{% endfor %}
