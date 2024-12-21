---
layout: default
title: "Premios y Reconocimientos"
permalink: /awards/
---

# Premios y Reconocimientos

Mi trabajo académico ha sido reconocido a través de diversos premios y distinciones, reflejo de la contribución teórica y práctica en el campo de las redes eléctricas inteligentes, el machine learning aplicado a la energía, y el análisis estocástico de recursos renovables.

## Premios Destacados

{% for award in site.data.awards %}
**{{ award.name }} ({{ award.year }})** - {{ award.institution }}  
{{ award.details }}

---
{% endfor %}

[Servicio Académico](service.md)
