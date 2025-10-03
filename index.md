---
layout: default
title: The Cognitive Review
---

# Welcome to My Research Journal


This is where I'll share my thoughts, findings, and academic musings.

**Recent entries:**

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %-d, %Y" }}
    </li>
  {% endfor %}
</ul>
