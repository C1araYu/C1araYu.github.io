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
* M.S. in Computer Science, Columbia Engineering, 2025 (Expected)
* B.E. in Information Security (IEEE honor), Shanghai Jiao Tong University, 2024

Research Interests
======
* **Trustworthy Machine Learning**:  
  Developing robust and secure learning frameworks in decentralized environments, including federated learning, distributed algorithms, backdoor attacks and defenses, differential privacy, and model compression techniques.  
  (*POLAR, Contribution Feedback Aggregation, W3FedPOSE, Enhanced Structured Lasso Pruning*)

* **Explainable AI**:  
  Designing interpretable and fairness-aware learning systems through Shapley-based contribution evaluation, incentive-aligned aggregation, and class-wise pruning guided by Information Bottleneck theory.  
  (*W3FedPOSE, Contribution Feedback Aggregation, Enhanced Structured Lasso Pruning*)

* **Computer Vision**:  
  Leveraging Vision Transformers for video-based state prediction and spatiotemporal modeling in dynamic systems.  
  (*State Variables Prediction with ViT*)
  
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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
