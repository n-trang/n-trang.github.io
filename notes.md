---
layout: default
title: "✍️notes"
---

## I write along as I learn. Also, some random thoughts and translations.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>