---
permalink: /
title: "Joon Park"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. student in Electrical Engineering working on computational imaging and adaptive optics. My research interests center on modeling optical systems and building adaptive imaging methods for dynamic samples.

## Research Interests

- Computational imaging
- Adaptive optics
- Optical system modeling
- Bio-optical imaging

## Publications

{% assign homepage_publications = site.publications | where_exp: "post", "post.published != false" | sort: "date" | reverse %}
{% for post in homepage_publications %}
  {% include archive-single.html %}
{% endfor %}

[View all publications](/publications/)

## Education

- Ph.D. in Electrical Engineering, 2026.03 - present
- M.S. in Electrical Engineering, 2024.03 - 2026.02
- B.S. in Electrical Engineering, 2019.09 - 2024.02

## Teaching Experience

Teaching experience and mentoring activities will be added here.

## Research and Other Experience

- Research collaboration with [Prof. Jung-Hoon Park's group @ UNIST](https://www.biooptics.org/) and [Prof. Jae-Byum Chang's group @ KAIST](https://sites.google.com/site/jbchang03/) on graph-based optical system modeling and adaptive optics.

## Honors and Awards

- Best Poster Award, SPIE Advanced Biophotonics Conference (ABC), 2025.
