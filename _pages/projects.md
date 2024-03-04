---
layout: page
title: projects
permalink: /projects/
nav: true
nav_order: 2
---

<div class="projects">
  {% assign sorted_projects = site.projects | sort: "importance" %}

  <div class="grid">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>

</div>