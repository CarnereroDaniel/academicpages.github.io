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
* Ph.D in Control Engineering, University of Seville, 2022
* M.S. in Industrial Engineering, University of Seville, 2019
* B.S. in Industrial Engineering, University of Seville, 2017

Work experience
======
* September, 2019 - November, 2022: Teaching Assistant
  * University of Seville

* January, 2023 - May, 2024: Postdoc
  * Tokyo Institute of Technology

* June, 2024 - Present: Assistant Professor
  * The University of Osaka

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
  
Service and leadership
======
* IFAC 2023, Student Activities Co-Chair, International Federation of Automatic Control
* Associate Editor of the 9th IFAC Symposium on System Structure and Control, 19th IFAC Workshop on Time Delay Systems and 2nd IFAC Workshop on Control of Complex Systems
