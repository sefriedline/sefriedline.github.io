---
layout: default
title: Research Interests
---
<h1>{{page.title}}</h1>

coming soon!

<u1>
  {% for project in site.research-interests %}
      <h2>{{ project.organization }}</h2>
      <h3>{{ project.position }}</h3>
      <h3>{{ project.dates }}</h3>
      <p>{{ project.content | markdownify }}</p>


  {% endfor %}
</u1>
