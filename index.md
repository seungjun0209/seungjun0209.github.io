---
layout: default
title: Home
---

<h1>최근 글</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%Y-%m-%d" }})</small>
      {% if post.categories %}
        <small> - {{ post.categories | join: ", " }}</small>
      {% endif %}
    </li>
  {% endfor %}
</ul>
