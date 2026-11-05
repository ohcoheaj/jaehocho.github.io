---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- TODO: add Education and Research Experience sections, e.g.

Education
======
* Degree, Institution, Year

Research Experience
======
* Position, Lab / Institution, Period
-->

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
