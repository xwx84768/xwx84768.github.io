---
layout: single
permalink: /
title: "Xiangwen Wang"
author_profile: true
---

Hi! I'm **Xiangwen Wang (王香雯)**, a first-year MSCS student at the University of Illinois Urbana–Champaign (UIUC), where I am fortunate to be advised by Professor [Varun Chandrasekaran](https://chandrasekaran-group.github.io/). I received my bachelor's degree from the School of the Gifted Young, University of Science and Technology of China (USTC), and I also spent a summer as a research intern at STAIR LAB, Stanford University.

My research interests lie broadly in **post-training for large language models** and **trustworthy AI**, with a focus on AI alignment, LLM security, and the reliability of multi-component and multi-agent systems.  
My long-term goal is to build AI systems that are **safe, robust, and value-aligned**, especially as they scale into complex, real-world settings.

---

## Research Interests

- **AI Alignment & Preference Learning**  
  Aligning LLMs with human values, improving preference-optimization algorithms, and aligning compound systems.

- **LLM Safety & Reliability**  
  Jailbreak and backdoor attacks, red-teaming, post-training safety, and scalable evaluations.

- **Multi-agent & Compound AI Systems**  
  Studying interactions, coordination, and optimization in multi-agent or multi-component AI systems.

---

## Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}