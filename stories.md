---
layout: default
title: Stories
permalink: /stories/
---

<h1>Stories</h1>

<ul>
  {% for post in site.categories.stories %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> – {{ post.date | date: "%b %d, %Y" }}
    </li>
  {% endfor %}
</ul>