---
layout: default
title: Centro de Descargas
parent: Español
nav_order: 16
slug: downloads
---
{% include lang_switch.html slug="downloads" %}
# Centro de Descargas
{% assign items = site.static_files | where_exp: "f", "f.path contains '/assets/files/es/' and f.name != '.gitkeep'" %}
{% if items.size > 0 %}{% for f in items -%}
- [{{ f.name }}]({{ f.path | relative_url }})
{%- endfor %}{% else %}_No hay archivos todavía._{% endif %}