---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="https://min9kwak.github.io/files/CV.pdf" target="_blank">My CV</a>

Education
======
* Ph.D in Industrial and Management Engineering, Korea University, 2022
* B.S. in Industrial and Management Engineering, Korea University, 2016

Work experience
======
* Postdoctoral Researcher, Apr. 2022 ~ Present
  * H. Milton Stewart School of Industrial and Systems Engineering
  * Artificial Intelligence for Medical Data Analysis and Integration for Clinical Usage
  * Supervisor: Prof. Jing Li

* Graduate Research Assistant, Mar. 2016 ~ Feb. 2022
  * Industrial and Management Engineering, Korea University
  * Work in various research projects to solve real-world industrial problems 
  * Supervisor: Prof. Seoung Bum Kim

Skills
======
* Programming Languages: Python (Advanced), R (Advanced), SQL (Proficient)
* Deep Learning Frameworks: Pytorch (Advanced), Keras (Advanced), Tensorflow (Proficient)
* Tools: Git (Proficient), Docker (Intermediate)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Selected Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Reviewer, INFORMS Journal of Computing, 2024
* Reviewer, IEEE Transactions on Automation Science and Engineering, 2023
* Sergeant, Korean Augmentation to the United States Army, 2011.09 ~ 2013.06
