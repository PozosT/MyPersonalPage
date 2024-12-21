---
layout: default
title: "Docencia"
permalink: /teaching/
---

# Docencia

Imparto cursos en pregrado y posgrado, integrando rigor matemático, aplicaciones prácticas y métodos avanzados. A continuación se listan algunos cursos, cargados desde `_data/courses.yml`:

{% for course in site.data.courses %}
## {{ course.name }}
**Nivel:** {{ course.level }}  
**Semestre:** {{ course.semester }}

{{ course.description }}

---
{% endfor %}

[Mi Filosofía Docente](philosophy.md)
