---
layout: page
title: resources
permalink: /resources/
description: >
  <span style="color: var(--global-theme-color); font-weight: bold;">Models</span>
  and
  <span style="color: #b509ac; font-weight: bold;">datasets</span>
  shared with the scientific community.
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
      <div class="project-flex-container">
        {% for project in sorted_projects %}
          <div class="project-flex-item">
            {% include projects.liquid %}
          </div>
        {% endfor %}
      </div>
    {% else %}
      <p>No projects in this category yet.</p>
    {% endif %}

  </section>
  {% endfor %}
</div>
