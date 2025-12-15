---
layout: page
title: Back
permalink: /category/back/
---

<ul>
  {% for post in site.posts %}
    {% if post.categories contains "Back" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a> <small>{{ post.date | date: "%Y-%m-%d" }}</small></li>
    {% endif %}
  {% endfor %}
</ul>
