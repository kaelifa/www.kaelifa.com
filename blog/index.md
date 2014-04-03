---
layout: default
title: "Blog"
description: ""
---

# {{ page.title }}

<ul class="entries">
  {% for post in site.posts %}

  <li>
    <span class="post__time">{{ post.date | date: "%d %B, %Y" }}</span>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>

  {% endfor %}
</ul>
