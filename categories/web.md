---
layout: default
title: Web Challenges
---

# 🌐 Web Writeups

{% for post in site.posts %}
  {% if post.categories contains "web" %}
  - [{{ post.title }}]({{ post.url }})
  {% endif %}
{% endfor %}
