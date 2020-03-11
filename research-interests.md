---
layout: default
title: Research Interests
---
<h1>{{page.title}}</h1>

coming soon!

<u1>
  {% for project in site.research-interests %}
      <h2>{{ project.organization }}</h2>
      <h3 style="margin-left: 2.5em;">{{ project.dates }}</h3>
      <p style="margin-left: 2.5em;">{{ project.content | markdownify }}</p>
      <br>
      <br>

  {% endfor %}
</u1>
