---
layout: archive
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
  
Research Experiences
======
### State Variables Prediction with ViT  
**Instructor**: Hod Lipson (Columbia University)  
📅 *Nov 2024 – Present*  
- Integrated Vision Transformers (ViT) into the TIDE framework to improve spatial-temporal feature extraction and state variable prediction from video sequences.  
- Proposed a federated learning architecture for distributed, privacy-preserving training across multiple devices without centralized raw data sharing.  
- Developed advanced training techniques—including mixed-precision training, KL warmup, and loss visualization—for robust performance on real-world dynamic systems.

---

### [Submitted to ICCV 2025] POLAR: Policy-based Layerwise Reinforcement Method for Stealthy Backdoor Attacks in Federated Learning  
**Instructors**: Hao Wang (Stevens Institute of Technology), Yang Hua (Queen’s University Belfast), Tao Song (Shanghai Jiao Tong University)  
📅 *July 2024 – March 2025*  
- Proposed **POLAR**, the first RL-based framework for backdoor attacks in federated learning by modeling layer selection as a reinforcement learning problem.  
- Combined reinforcement learning with layerwise poisoning to adapt dynamically using real-time feedback on backdoor success rate (BSR).  
- Achieved superior performance over LP Attack and BadNets in BSR, main task accuracy, and malicious client acceptance rate (MAR) across various benchmarks.

---

### [To be submitted] Contribution Feedback Aggregation Algorithm in Federated Learning  
**Instructors**: Tao Song, Ke Xu (Shanghai Jiao Tong University)  
📅 *Jan 2024 – May 2024*  
- Developed a novel explainable aggregation algorithm that integrates feedback from incentive mechanisms to support robust and fair FL aggregation.  
- Mitigated the negative impact of low-quality participants by feeding back contribution evaluation into traditional aggregation processes.  
- Demonstrated faster convergence and higher accuracy in large-scale or low-quality-user-dominated federated training environments.

---

### [Submitted to The Web Conf 2024] W3FedPOSE: A Practical WEB3.0-Based Federated Learning Framework  
**Instructors**: Yang Hua (Queen’s University Belfast), Tao Song (Shanghai Jiao Tong University)  
📅 *April 2023 – Oct. 2023*  
- Proposed **FedTreeSHAP**, a linear-time Shapley approximation algorithm for efficient and fair participant contribution evaluation in Web3-based FL.  
- Designed a contribution allocation method that reduces complexity from \( O(2^n) \) to \( O(n) \) using tree computation structures.  
- Validated the approach on multiple benchmarks, outperforming other approximations in accuracy while maintaining the same order of computational cost.

Awards
======
- **Leading Cyber Security Scholarship** — *Top 5%*, awarded based on comprehensive performance  
  *2023*

- **Zhiyuan Honour Scholarship** — *Top 5%*, awarded based on academic excellence  
  *2020, 2021*
