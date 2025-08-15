---
layout: default
title: Home
---

# Welcome to My Minimal Jekyll Blog

This is a simple, clean blog powered by Jekyll and GitHub Pages.

## Recent Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> <small>{{ post.date | date: "%b %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
