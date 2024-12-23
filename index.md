---
layout: default
title: Home
---

# Welcome to matkalkyl.dev

This is the homepage for the site. Below, you'll find links to the newsletters:

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.date | date: "%B %Y" }} - {{ post.title }}</a>
  </li>
  {% endfor %}
</ul>
