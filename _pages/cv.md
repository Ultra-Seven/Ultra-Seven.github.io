---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Software Engineering, Fudan University, 2018
* Ph.D in Computer Science, Cornell University, 2024 (expected)

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Work experience
======
* Summer 2021: MSR Data Systems Lab
  * Research: Query optimization
  * Mentor: Bailu Ding
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
