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
* B.S. in Computer Sciences, University of Wisconsin-Madison, 2026 (expected)

Research experience
======
* Fall 2025: Undergraduate Research Intern
  * University of Wisconsin-Madison, [Robot Teaching and Teaming Lab](https://wisc-rt2.github.io/)

* Summer 2025: Undergraduate Research Intern
  * Boise State University
  * see our project presentation [here!](https://scholarworks.boisestate.edu/icur/2025/poster_session/85/)
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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