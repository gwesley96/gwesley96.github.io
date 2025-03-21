---
title: "Files"
permalink: /files/
author_profile: true
redirect_from:
  - /files/
published: true
layout: archive
---

<table>
  <thead>
    <tr>
      <th>Name</th>
      <!-- <th>Last Modified</th>
      <th>Size</th> -->
    </tr>
  </thead>
  <tbody>
    {% assign math_files = site.static_files | where_exp: "file", "file.path contains '/files/'" %}
    {% for file in math_files %}
      <tr>
        <td><a href="{{ file.path | relative_url }}">{{ file.name }}</a></td>
        <!-- <td>{{ file.modified_time | date: "%Y-%m-%d %H:%M" }}</td>
        <td>{{ file.size | divided_by: 1024 | round: 2 }} KB</td> -->
      </tr>
    {% endfor %}
  </tbody>
</table>