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
* Classe Préparatoires in Physics and Chemistry (PCSI/PS*), Lycée La Martinière Monplaisir Lyon, 2015-2017
* License in Fundamental Physics, Université Claude Bernard Lyon I (UCBL), 2017-2018
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
