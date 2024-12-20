---
layout: default
title: "Proyectos Financiados"
---

# Proyectos Financiados (Grants) y Colaboraciones

A lo largo de mi carrera he participado en y liderado múltiples proyectos financiados por agencias nacionales e internacionales. Estos proyectos tienen una sólida base matemática y un enfoque computacional avanzado, orientado al análisis y optimización de sistemas de potencia con alta penetración renovable, la teoría del aprendizaje automático, y la integración estocástica de recursos energéticos distribuidos.

## Proyectos Destacados
{% for proj in site.data.projects %}
### {{ proj.title }}
**Financiado por:** {{ proj.funding }}  
**Período:** {{ proj.period }}  
**Rol:** {{ proj.role }}

{{ proj.summary }}

---
{% endfor %}

[Volver a Investigación](research.md)
