---
layout: page
title: Mes Projets
permalink: /projects/
order: 3
---

Voici une sélection de mes réalisations académiques et personnelles.

## Liste des projets

{% for project in site.projects %}
- [**{{ project.title }}**]({{ project.url | relative_url }}) : {{ project.description }}
{% endfor %}

