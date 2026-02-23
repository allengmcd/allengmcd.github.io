---
layout: page
title: My Projects
permalink: /projects/
---

Below is a collection of my recent work and technical experiments.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
