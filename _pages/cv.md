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
* B.S. in Computational Mathematics, Dalian University of Technology, 2022

#Work experience
#======
#* Spring 2024: Academic Pages Collaborator
#  * Github University
#  * Duties includes: Updates and improvements to template
#  * Supervisor: The Users

#* Fall 2015: Research Assistant
#  * Github University
#  * Duties included: Merging pull requests
#  * Supervisor: Professor Hub

#* Summer 2015: Research Assistant
#  * Github University
#  * Duties included: Tagging issues
#  * Supervisor: Professor Git

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* President of the [SIAM Student Chapter of City University of Hong Kong](https://www.cityu.edu.hk/ma/siam-cityuhk-student-chapter)
