---
layout: page
title: Resources
permalink: /resources/
description: >
  Models and Datasets shared with the scientific community.
nav: true
nav_order: 3
display_categories: [model, data]
horizontal: false
---

<!-- pages/projects.md -->

<div class="projects">
  {% for category in page.display_categories %}
  <section id="{{ category }}" class="project-category">
    <h2 class="category">
      {% case category %}
        {% when "model" %} Models and Code
        {% when "data" %} Datasets
        {% else %} {{ category }}
      {% endcase %}
    </h2>

    {% assign categorized_projects = site.projects | where: "category", category %}
    {% assign sorted_projects = categorized_projects | sort: "importance" %}

    {% if sorted_projects.size > 0 %}
      {% if sorted_projects.size > 0 %}

  <ul class="project-list">
    {% for project in sorted_projects %}
      <li class="project-list-item">
        <a href="{{ project.url | relative_url }}" class="project-link">
          {{ project.title }}
        </a>
      </li>
    {% endfor %}
  </ul>
{% else %}
  <p>No projects in this category yet.</p>
{% endif %}
    {% else %}
      <p>No projects in this category yet.</p>
    {% endif %}

  </section>
  {% endfor %}
</div>
