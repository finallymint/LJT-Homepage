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
* Ph.D. in Computer Science, Hong Kong University of Science and Technology, 2024-Present
* B.Eng., Shanghai Jiao Tong University, 2020-2024

Work experience
======
* February 2025 - Present: Research Intern
  * MINIMAX
  * Working on large language models

* June 2024 - September 2024: Research Intern
  * Tencent WXG
  * Advised by Zifei Shan

* June 2023 - December 2023: Research Intern
  * Shanghai AI Lab
  * Advised by Prof. Yu Cheng

Skills
======
* Natural Language Processing
* Machine Learning
* Large Language Models
* Vision-Language Models
* Reinforcement Learning

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
