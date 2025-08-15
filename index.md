---
layout: default
title: Home
---


<div style="text-align:center; margin-top:2em;">
  <img src="https://pbs.twimg.com/profile_images/1876393154099740672/7iLAPmhD_400x400.jpg" alt="Profile Photo" style="width:120px; border-radius:50%; margin-bottom:1em;">
  <h1 style="font-size:2.5em; margin-bottom:0.2em;">Your Name</h1>
  <p style="font-size:1.2em;">Hi! 👋</p>
</div>

<hr>

<ul style="list-style:none; padding:0;">
  {% for post in site.posts %}
    <li style="margin-bottom:1.5em;">
      <a href="{{ post.url }}" style="font-size:1.3em; font-weight:bold;">{{ post.title }}</a><br>
      <span style="color:#888; font-size:0.95em;">{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
