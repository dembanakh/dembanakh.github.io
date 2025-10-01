---
layout: home
author_profile: true
---

I'm a PhD student at Jagiellonian University (Kraków, Poland).
Doing research in Constraint Satisfaction Problems under the supervision of Marcin Kozik.

## Recent
<ul>
{% for post in site.posts limit:5 %}
  <li>
    <span>{{ post.date | date: "%-d %b" }}</span> — 
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

