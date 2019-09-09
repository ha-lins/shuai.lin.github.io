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
* Ph.D in Computer Science, Georgia Institute of Technology, 2019 - Present 
* B.E. in Computer Science and Technology, Zhejiang University, 2015 - 2019

Skills and Interests
======
* Technology and Language Skills:
  * Programming Languages: C/C++, Python, Verilog, Matlab, Labview, SQL, C#, Lex/Yacc.
  * Development Skills: Pytorch, Tensorflow, OpenCV, QT. 
* Piano (Level 10 Certificate), Basketball.

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
  

