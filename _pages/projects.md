---
layout: page
title: resources
permalink: /resources/
description: <span style="color:#EF476F; font-weight:bold;">Models</span> and <span style="color:#12B589; font-weight:bold;">datasets</span> shared with the scientific community. <span style="color:#EF476F; font-weight:bold;">THIS PAGE IS UNDER CONSTRUCTION</span>
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
        {% when "model" %} models and code
        {% when "data" %} datasets
        {% else %} {{ category }}
      {% endcase %}
    </h2>

    {% assign categorized_projects = site.projects | where: "category", category %}
    {% assign sorted_projects = categorized_projects | sort: "importance" %}

    {% if sorted_projects.size > 0 %}
      {% if page.horizontal %}
      <div class="container">
        <div class="row row-cols-1 row-cols-md-4 project-row-small">
          {% for project in sorted_projects %}
            {% include projects_horizontal.liquid %}
          {% endfor %}
        </div>
      </div>
      {% else %}
      <div class="row row-cols-1 row-cols-md-4 project-row-small">
        {% for project in sorted_projects %}
          {% include projects.liquid %}
        {% endfor %}
      </div>
      {% endif %}
    {% else %}
      <p>No projects in this category yet.</p>
    {% endif %}

  </section>
  {% endfor %}

</div>