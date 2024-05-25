---
title: Ormesome on GitHub
description: Projects
---

<ul>
  {% for project in site.projects %}
    <li>
      <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
      <p>{{ project.excerpt | markdownify }}</p>
    </li>
  {% endfor %}
</ul>
