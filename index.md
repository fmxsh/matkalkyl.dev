---
layout: default
title: Home
---

# Matkalkyl.dev

Denna sida är tillägnad utvecklingen av Matkalkyl.

En ny version av Matkalkyl.se är fortfarande på gång.

Du kan alltid komma till denna sida för den senaste informationen.

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}"> {{ post.title }}</a>
  </li>
  {% endfor %}
</ul>
