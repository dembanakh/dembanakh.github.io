---
layout: home
author_profile: true
---

# Welcome

I'm a PhD student at Jagiellonian University (Kraków, Poland).
Doing research in Constraint Satisfaction Problems.

## Recent News
{% for post in site.posts limit:5 %}
- {{ post.date | date: "%b %Y" }}: [{{ post.title }}]({{ post.url }})
{% endfor %}

