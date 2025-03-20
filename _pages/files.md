---
title: "Files"
permalink: /files/
author_profile: true
redirect_from:
  - /notes/
  - /files/
published: true
layout: archive
---

# Files

<ul>
  {% for file in site.static_files %}
    {% if file.path contains '/files/' %}
      <li><a href="{{ file.path | relative_url }}">{{ file.name }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
