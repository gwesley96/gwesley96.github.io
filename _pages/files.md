---
title: "Files"
permalink: /files/
author_profile: true
redirect_from:
  - /files/
published: true
layout: archive
---
<ul>
  {% for file in site.static_files %}
    {% if file.path contains '/files/' %}
      <li>
        <a href="{{ file.path | relative_url }}">{{ file.name }}</a>
        (Last updated: {{ file.modified_time | date: "%Y-%m-%d at %I:%M %p" }} ET)
      </li>
    {% endif %}
  {% endfor %}
</ul>
