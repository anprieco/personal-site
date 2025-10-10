---
title: Education
nav:
  order: 5
  tooltip: Academic path
---

# {% include icon.html icon="fa-solid fa-graduation-cap" %}Education

A look at the studies and mentors that shaped my way of thinking and guided me into neuroscience research.

{% include tags.html tags="Alicante, Barcelona" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="education" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="education" filter="!group" style="small" %}
