---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download my CV here](/files/Kishen_Senziani_CV_PhD.pdf)

Education
======
* M.Sc. in Interdisciplinary Neuroscience, University of Geneva (UNIGE), in progress
* M.Sc. in Advanced Research in Psychology, University of Geneva (UNIGE), in progress

Research Experience
======
* Current: Graduate Researcher
  * University of Geneva, Neuroscience Department
  * Characterizing word processing pathways using frequency tagging
  * Focus: Language processing and cognitive neuroscience

Skills
======
* **Behavioral Science & Experimental Design**
* **Neuroimaging**
  * fMRI
  * EEG
  * MEG
* **Data Analysis**
  * R
  * Python

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
