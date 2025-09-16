---
layout: default
title: "CySec Blog"
---

# Adventures in Cybersecurity

Welcome to my cybersecurity blog. Here you’ll find all posts listed by date:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%B %d, %Y" }})</small>
    </li>
  {% endfor %}
</ul>
