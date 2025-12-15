---
layout: page
title: LGCNS
permalink: /category/lgcns/
---

<ul>
  {% for post in site.posts %}
    {% if post.categories contains "LGCNS" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a> <small>{{ post.date | date: "%Y-%m-%d" }}</small></li>
    {% endif %}
  {% endfor %}
</ul>
