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
* Ph.D in Mathematics, Michigan State University, 2023
* Bachelors in Physics/Applied Mathematics/Economics, Missouri S&T, 2018

Work experience
======
* 2023-Present: Risk Data Analytics Associate
  * Global Atlantic Financial Group, Risk Data Analytics
  * Duties includes: Training Large scale surrender models to update yearly assumptions. 

* Sunmmer 2023: Risk Data Analytics Intern
  * Global Atlantic Financial Group, Risk Data Analytics
  * Duties includes: Training surrender models for variable annuity blocks. 

* Summer 2022: Data Science Intern
  * Amazon, B2B Payments 
  * Duties included: Created scalable B2B fraud model in the amazon fraud detection pipeline. Saved $20mm in fraud losses.

* 2018 - 2023: Graduate Research/Teaching Assistant
  * Michigan State University
  * Duties included: Taught undergraduate courses at MSU. Please see teaching portion below.
    
* 2018 - 2023: Grader/Releaser
  * Art of Problem Solving
  * Duties included: Graded problems for AoPS courses, which are made for talented K-12 students to training for high school olympiads. 
  
Skills
======
* C++
  * OpenMP
  * MPI
* Python
  * Numpy
  * Pandas
  * Sk-learn
  * Pytorch
* MATLAB
* LaTeX

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

