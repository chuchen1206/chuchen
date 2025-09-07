---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. Student, Department of Mathematics, City University of Hong Kong, 2022-2026
* Visiting Ph.D. Student, Department of Applied Mathematics and Theoretical Physics, University of Cambridge, 2025
* B.S. in Computational Mathematics, Dalian University of Technology, 2018-2022

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service
======
* President of the [SIAM CityUHK Student Chapter](https://www.cityu.edu.hk/ma/siam-cityuhk-student-chapter)
