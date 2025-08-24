---
layout: archive
title: "PDF Library"
permalink: /teaching/2025_fall_5615h_notes
author_profile: false
---

---
layout: default
title: "PDF Library"
---

# PDF Files

<ul>
  {% for file in site.static_files %}
    {% if file.path contains '/math/_teaching/test/' and file.extname == '.pdf' %}
      <li><a href="{{ file.path }}">{{ file.name }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
