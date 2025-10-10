---
title: Experience
nav:
  order: 2
  tooltip: Scientific journey
---

# {% include icon.html icon="fa-solid fa-wrench" %}Experience

A snapshot of my scientific path: From research training to projects that shaped my skills, collaborations, and curiosity.

{% include tags.html tags="regeneration, neurodegeneration, neurodevelopment, neuro-oncology" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
