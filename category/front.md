---
layout: page
title: Front
permalink: /category/front/
---

<ul>
  {% for post in site.posts %}
    {% if post.categories contains "Front" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a> <small>{{ post.date | date: "%Y-%m-%d" }}</small></li>
    {% endif %}
  {% endfor %}
</ul>
