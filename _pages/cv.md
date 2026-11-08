---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- TODO: put a PDF of your CV at files/cv.pdf, then uncomment the next line. -->
<!-- [Download my CV as a PDF]({{ base_path }}/files/cv.pdf) -->

Education
======
* PhD in Plasma Physics, <!-- TODO: university -->, <!-- TODO: start year -->–present (expected <!-- TODO -->)
  * Thesis topic: Doppler backscattering and beam tracing <!-- TODO: exact title / supervisor(s) -->
* <!-- TODO: previous degree, institution, year -->

Research experience
======
* <!-- TODO: e.g. experimental campaigns, visits to other labs -->

Software
======
* Core developer of [Scotty](https://github.com/beam-tracing/Scotty), a beam-tracing code for Doppler backscattering (v4 rewrite)

Skills
======
* Python (NumPy, SciPy, xarray), scientific software development, testing and version control
* <!-- TODO: others -->

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

Awards and service
======
* <!-- TODO -->
