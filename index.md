---
layout: default
title: Home
---

# Salvation and the Risen King

Essays exploring union with Christ, the kingdom of God, and faith as allegiance to the risen King.

This site contains essays and reflections related to my forthcoming book *Salvation and the Risen King*.

## Essays

{% for post in site.posts %}

### [{{ post.title }}]({{ post.url }})

{{ post.date | date: "%B %d, %Y" }}

{% endfor %}
