---
title: Jekyll, you were whom I was looking for
layout: default
category: web
tags: [starting, jekyll]
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>