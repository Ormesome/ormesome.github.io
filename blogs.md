---
title: Ormesome on GitHub
description: Latest Posts
---

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
      <p>Categories: {{ post.categories | array_to_sentence_string}}</p>
    </li>
  {% endfor %}
</ul>
