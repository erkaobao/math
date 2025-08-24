---
layout: archive
title: "2025 Fall 5615H lecture notes"
permalink: /teaching/2025_fall_5615h_notes
author_profile: false
---

<ul>
  {% for file in site.static_files %}
    {% if file.path contains '/test/' and file.extname == '.pdf' %}
    <li><a href="{{ '/math' | append: file.path }}">{{ file.name }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
