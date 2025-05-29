---
title: "Notes"
permalink: /files/
author_profile: true
redirect_from:
  - /files/
  - /notes/
published: true
layout: archive
---


<!-- - [Algebraic topology](AlgebraicTopology) -->
<!-- ### Algebraic higher (unitary) categories and more
- [Algebraic higher (unitary) categories and more](AlgebraicHigherCategories.pdf) -->

### Brief notes
- [Kan extensions](KanExtensions.pdf)

- [Representability](Representability.pdf)

- [Canonical quantization](CanonicalQuantization.pdf)

### Longer notes
- [Algebraic topology, tersely](AlgebraicTopologyTersely.pdf)

### All files
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

### Useful links 
- [Taylor’s theorem with remainder (single and multivariable)](https://web.archive.org/web/20231207050408/https://www3.nd.edu/~nancy/Math40760/Info/taylor.pdf)