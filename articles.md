---
layout: default
title: Articles
permalink: /articles/
---

<h1>Articles</h1>

<ul>
  {% for post in site.categories.articles %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> – {{ post.date | date: "%b %d, %Y" }}
    </li>
  {% endfor %}
</ul>