---
layout: default
title: "Dirección de Tesis y Estudiantes"
permalink: /students/
---

# Dirección de Tesis y Estudiantes

La formación de nuevos investigadores es esencial en mi labor académica. A continuación, una lista de estudiantes que he supervisado (datos de `_data/students.yml`):

{% for stu in site.data.students %}
### {{ stu.name }}
**Nivel:** {{ stu.level }}  
**Período:** {{ stu.period }}  
**Tesis:** {{ stu.thesis_title }}

{{ stu.details }}

---
{% endfor %}

[Actividades de Extensión](outreach.md)
