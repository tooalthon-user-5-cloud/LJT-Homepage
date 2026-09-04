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
* Ph.D. in Computer Science, Hong Kong University of Science and Technology (HKUST), 2024–present
* B.Eng., Shanghai Jiao Tong University (SJTU), 2020–2024
  * Received the Zhiyuan Honor Scholarship

Work experience
======
* Research Intern, MINIMAX, February 2025 – present
* Research Intern, Tencent WXG, June 2024 – September 2024
* Research Intern, Shanghai AI Lab, June 2023 – December 2023

Skills
======
* Natural Language Processing
* Machine Learning
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models (VLMs)
* LLM Truthfulness and Interpretability

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
