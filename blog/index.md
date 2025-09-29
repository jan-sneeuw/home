---
layout: default
title: "Blog"
---

# Cybersecurity Blog

Welcome to my cybersecurity blog! I am planning on posting small tid-bits, write-ups of CTF-challenges and learning experiences that are connected to cybersecurity in some way and that I found interesting.

<div class="blog-list">
  {% for post in site.posts %}
    <a href="{{ post.url | relative_url }}" class="blog-card">
      <h3>{{ post.title }}</h3>
      <p>{{ post.excerpt }}</p>
      <p class="blog-date">{{ post.date | date: "%B %d, %Y" }}</p>
    </a>
  {% endfor %}
</div>
