---
layout: archive
title: "PDF Library"
permalink: /teaching/2025_fall_5615h_notes
author_profile: false
---

# PDF Files

<ul>
  {% for file in site.static_files %}
    {% if file.path contains '/test/' and file.extname == '.pdf' %}
      <li><a href="{{ site.baseurl }}{{ file.path }}/math/">{{ file.name }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
