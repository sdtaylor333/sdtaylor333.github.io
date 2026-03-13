---
layout: default
title: Essays
---

## Essays

{% for post in site.posts %}

### <a href="{{ post.url }}">{{ post.title }}</a>

<p style="margin-top:-8px; color:#666;">
{{ post.date | date: "%B %-d, %Y" }}
</p>

{% endfor %}
