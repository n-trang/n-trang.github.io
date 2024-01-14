---
layout: default
title: "✍️notes"
permalink: /notes/
---

## I write along as I learn. Also some translations.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>