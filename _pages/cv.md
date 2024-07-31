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
* 2022-2025 (expected): Ph.D in Statistics, Statistical inference on dependent data, Université Paris-Saclay.
* 2021-2022: Master 2 Mathematics of randomness, Probability & Statistics track, Université Paris-Saclay.
* 2018-2022: Diplôme d'ingénieur, Applied mathematics & Computer science, CentraleSupélec.

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
