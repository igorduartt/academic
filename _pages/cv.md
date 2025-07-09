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
* Ph.D in Psychiatry, University of São Paulo, 2024 (expected)
* M.S. in Psychiatry and Behavioral Sciences, Federal University of Rio Grande do Sul, 2021
* B.S. in Psychology, 2019

Work experience
======
* 2022-Present: Research Assistant
  * University of São Paulo
  * Duties include: Data analysis, machine learning model development, clinical research
  * Supervisor: Research Advisor

* 2020-2022: Clinical Psychologist
  * Private Practice
  * Duties included: Psychological assessment, therapy sessions, clinical documentation
  * Supervisor: Clinical Director

* 2019-2020: Data Analyst
  * Healthcare Institution
  * Duties included: Statistical analysis, report generation, data visualization
  * Supervisor: Data Manager
  
Skills
======
* Data Analysis
  * Python (pandas, numpy, scikit-learn)
  * R (tidyverse, ggplot2, statistical modeling)
  * SPSS
* Machine Learning
  * Supervised learning algorithms
  * Model validation and evaluation
  * Feature engineering
* Clinical Research
  * Study design
  * Statistical analysis
  * Report writing
* Psychology
  * Psychological assessment
  * Clinical interviewing
  * Therapeutic techniques

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
  
Service and leadership
======
* Peer reviewer for academic journals
* Member of research ethics committee
* Mentor for undergraduate students
