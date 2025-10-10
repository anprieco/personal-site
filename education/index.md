---
title: Education
nav:
  order: 3
  tooltip: Academic path
---

# {% include icon.html icon="fa-solid fa-wrench" %}Education

A look at the studies and mentors that shaped my way of thinking and guided me into neuroscience research.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
