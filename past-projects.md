---
layout: default
title: Past Projects
---
<h1>{{page.title}}</h1>



<u1>
  {% for project in site.past-projects %}
      <h2>{{ project.organization }}</h2>
      <h3>{{ project.position }}</h3>
      <h3>{{ project.dates }}</h3>
      <p>{{ project.content | markdownify }}</p>


  {% endfor %}
</u1>
