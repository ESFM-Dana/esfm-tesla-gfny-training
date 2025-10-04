---
layout: default
title: Download Center
nav_order: 16
slug: downloads
---
{% include lang_switch.html slug="downloads" %}
# Download Center
{% assign items = site.static_files | where_exp: "f", "f.path contains '/assets/files/en/' and f.name != '.gitkeep'" %}
{% if items.size > 0 %}{% for f in items -%}
- [{{ f.name }}]({{ f.path | relative_url }})
{%- endfor %}{% else %}_No files yet._{% endif %}