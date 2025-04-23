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
* **Trustworthy ML**:  
  Federated learning, distributed algorithms, and efficient model compression techniques for reliable and scalable machine learning.  
  (*POLAR, Contribution Feedback Aggregation, W3FedPOSE, Enhanced Structured Lasso Pruning*)

* **Privacy and Security**:  
  Adversarial attacks and defenses in federated settings, stealthy backdoor injection, and privacy-preserving learning with differential privacy.  
  (*POLAR, State Variables Prediction, W3FedPOSE*)

* **Explainable AI**:  
  Shapley-based contribution evaluation, incentive-aware aggregation, and class-wise interpretability in pruning and collaborative learning systems.  
  (*W3FedPOSE, Contribution Feedback Aggregation, Enhanced Structured Lasso Pruning*)
  
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
