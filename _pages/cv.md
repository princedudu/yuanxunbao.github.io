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
* B.Sc., M.Sc in Applied Mathematics, Simon Fraser University, 2011, 2012
  * Supervisor: Prof. [David Muraki](http://people.math.sfu.ca/~muraki/)
  * Thesis (M.Sc): [*On the parametric instabilities of internal gravity waves in a density-stratified fluid.*](http://summit.sfu.ca/item/12424)
* Ph.D in Mathematics, Courant Institute of Mathematical Sciences, New York University, 2018 (expected)
  * Advisor: Prof. [Aleksandar Donev](http://cims.nyu.edu/~donev/)
  * Dissertation topic: *Efficient and accurate numerical methods for simulating fluid-strucutre interactions.*

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
