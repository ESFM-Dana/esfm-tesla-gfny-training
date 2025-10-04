---
layout: default
title: مركز التنزيلات
parent: العربية
nav_order: 16
slug: downloads
---
{% include lang_switch.html slug="downloads" %}
<div dir="rtl" lang="ar" markdown="1">
# مركز التنزيلات
{% assign items = site.static_files | where_exp: "f", "f.path contains '/assets/files/ar/' and f.name != '.gitkeep'" %}
{% if items.size > 0 %}{% for f in items -%}
- [{{ f.name }}]({{ f.path | relative_url }})
{%- endfor %}{% else %}_لا توجد ملفات بعد._{% endif %}
</div>