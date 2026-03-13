---
layout: default
title: Essays
---

## Essays

<ul>
{% for post in site.posts %}
<h3>
<a href="{{ post.url }}">{{ post.title }}</a>
</h3>

<p style="margin-top:-10px; color:#666;">
{{ post.date | date: "%B %-d, %Y" }}
</p>

{% endfor %}
</ul>
