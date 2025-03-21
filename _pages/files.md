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
  {% assign files_in_directory = site.static_files | where_exp: "file", "file.path contains '/files/'" %}
  {% assign sorted_files = files_in_directory | sort: "modified_time" | reverse %}
  {% for file in sorted_files %}
    <li><a href="{{ file.path | relative_url }}">{{ file.name }}</a> (Last updated: {{ file.modified_time | date: "%Y-%m-%d at %H:%M %Z" }})</li>
  {% endfor %}
</ul>