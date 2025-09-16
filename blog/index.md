---
layout: default
title: "CySec"
---

# Adventures in Cybersecurity

Welcome to my cybersecurity blog. I am planning on posting small tid-bits, write-ups of CTF challenges and learning experiences in cybersecurity.

<ul>
  {% for post in site.posts %}
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt }}</p>
  {% endfor %}
</ul>
