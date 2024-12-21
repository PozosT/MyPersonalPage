---
layout: default
title: "Publicaciones"
permalink: /publications/
---

# Publicaciones

## Artículos en Revistas
{% for art in site.data.publications.articles %}
**"{{ art.title }}"** - {{ art.journal }} ({{ art.year }})  
{{ art.description }}

{% endfor %}

## Conferencias
{% for conf in site.data.publications.conferences %}
**"{{ conf.title }}"** - {{ conf.conference }} ({{ conf.year }})  
{{ conf.description }}

{% endfor %}

## Libros
{% for book in site.data.publications.books %}
**"{{ book.title }}"** - {{ book.publisher }} ({{ book.year }})  
{{ book.description }}

{% endfor %}

[Proyectos Financiados](grants.md)
