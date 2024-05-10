---
layout: home
description: "Department of Statistics Visva-Bharati. Meet faculties, students and alumnis. Explore our department, lecture notes, previous year question, and other resources."
---


<ul>
  {% for page in site.pages %}
    {% if page.path contains '_pages/' %}
      <li><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
