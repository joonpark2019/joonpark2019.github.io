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
* Ph.D. in Electrical Engineering, 2026.03 - present
* M.S. in Electrical Engineering, 2024.03 - 2026.02
* B.S. in Electrical Engineering, 2019.09 - 2024.02

Research interests
======
* Computational imaging
* Adaptive optics
* Optical system modeling
* Bio-optical imaging

Publications
======
  <ul>{% assign cv_publications = site.publications | where_exp: "post", "post.published != false" | sort: "date" | reverse %}
  {% for post in cv_publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching experience
======
* Teaching experience and mentoring activities will be added here.

Research and other experience
======
* Research collaboration with [Prof. Jung-Hoon Park's group @ UNIST](https://www.biooptics.org/) and [Prof. Jae-Byum Chang's group @ KAIST](https://sites.google.com/site/jbchang03/) on graph-based optical system modeling and adaptive optics.

Honors and awards
======
* Best Poster Award, SPIE Advanced Biophotonics Conference (ABC), 2025.
