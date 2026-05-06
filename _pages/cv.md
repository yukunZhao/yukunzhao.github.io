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
* Ph.D. in Computer Science and Technology, Shandong University, 2020 - 2024
* M.S. in Computer Science and Technology, Shandong University, 2014 - 2017
* B.S. in Software Engineering, Northeastern University, 2010 - 2014

Work Experience
======
* **Associate Professor** | School of Artificial Intelligence, Shandong University | Dec 2025 - Present
* **Staff Engineer** | Search Strategy Department, Baidu Inc. | Sep 2020 - Dec 2025
* **Senior Engineer** | Recommendation Algorithm Department, Alibaba Group | Apr 2019 - Sep 2020
* **Engineer** | Recommendation Algorithm Department, JD.com, Inc. | Jun 2017 - Apr 2019

Research Interests
======
* Natural Language Processing (NLP)
* Information Retrieval (IR)
* Large Language Models (LLMs)
* Language Agents
* Retrieval-Augmented Generation (RAG)
* Multimodal Learning

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
