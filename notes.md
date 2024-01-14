---
layout: default
title: "✍️notes"
permalink: /notes/
---

## I write along as I learn. Also some translations.

<ul class="postul">
  {% for post in site.posts %}
    <li>
      <h4><a href="{{ post.url }}">{{ post.title }}</a></h4>
    </li>
  {% endfor %}
</ul>