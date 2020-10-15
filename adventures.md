---
layout: default
title: Adventures
---
<h1>{{page.title}}</h1>



<u1>
  {% for project in site.adventures %}
      <h2>{{ project.organization }}</h2>
      <h3 style="margin-left: 2.5em;">{{ project.dates }}</h3>
      <p>{{ project.content | markdownify }}</p>
      <br>
      <br>

  {% endfor %}
</u1>
