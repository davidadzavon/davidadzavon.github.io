---
layout: page
title: Research
permalink: /projects/
description: Research papers and ongoing work.
nav: true
nav_order: 3
display_categories: [Submitted, Working Paper, Work in progress]
horizontal: true
---

<div class="projects">
{% for category in page.display_categories %}
  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  {% if sorted_projects.size > 0 %}
    <a id="{{ category }}" href=".#{{ category }}" style="text-decoration: none;">
      <h2 class="category" style="font-size: 1.8rem; font-weight: 800; color: var(--global-text-color); margin-top: 2.5rem; margin-bottom: 1.5rem; border-bottom: 3px solid var(--global-theme-color); padding-bottom: 0.6rem;">
        {{ category }}
      </h2>
    </a>
    <div class="container">
      <div class="row row-cols-1">
        {% for project in sorted_projects %}
          {% include projects_horizontal.liquid %}
        {% endfor %}
      </div>
    </div>
  {% endif %}
{% endfor %}
</div>