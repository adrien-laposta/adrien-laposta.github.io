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
* Master in Subatomic Physics and Cosmology, Université Grenoble Alpes (UGA), 2018-2020
* Preparation of a Ph.D in Cosmology, IJCLab (Orsay), Université Paris-Saclay, 2020-2023; Advisor : Thibaut Louis

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
