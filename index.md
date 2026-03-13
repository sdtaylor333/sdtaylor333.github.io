---
layout: default
title: Home
---

Essays exploring union with Christ, the kingdom of God, and faith as allegiance to the risen King.

These writings develop themes from my upcoming book Salvation and the Risen King.

## Essays

{% for post in site.posts %}

### [{{ post.title }}]({{ post.url }})

{{ post.date | date: "%B %d, %Y" }}

{% endfor %}
