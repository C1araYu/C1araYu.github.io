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
* **Web Agents**:  
  Investigating the robustness, perception, and decision-making of multimodal web agents under diverse visual and structural webpage variations, aiming to enhance their reliability, interpretability, and human alignment in real-world web environments.
(*What do Web Agents Look at?  A Comprehensive Evaluation of How Web Design and Visual Elements Affect Web Agents*)
  
* **Computer Vision**:  
  Leveraging Vision Transformers for video-based state prediction and spatiotemporal modeling in dynamic systems.  
  (*State Variables Prediction with ViT*)
  
* **Trustworthy Machine Learning**:  
  Developing robust and secure learning frameworks in decentralized environments, including federated learning, distributed algorithms, backdoor attacks and defenses, differential privacy, and model compression techniques.  
  (*POLAR, Contribution Feedback Aggregation, W3FedPOSE, Enhanced Structured Lasso Pruning*)

* **Explainable AI**:  
  Designing interpretable and fairness-aware learning systems through Shapley-based contribution evaluation, incentive-aligned aggregation, and class-wise pruning guided by Information Bottleneck theory.  
  (*W3FedPOSE, Contribution Feedback Aggregation, Enhanced Structured Lasso Pruning*)
  
Research Experiences
======
### What do Web Agents Look at? A Comprehensive Evaluation of How Web Design and Visual Elements Affect Web Agents  
**Instructor**: [Huan Zhang (University of Illinois Urbana-Champaign)](https://huan-zhang.com/)  
*July 2025 – Present*  
- Introduced **WebAgentsLook**, the first large-scale evaluation pipeline that systematically generates hundreds of CSS-based HTML variants by altering color, typography, and layout to isolate how visual design influences web agents’ decisions without changing underlying content.  
- Proposed a **three-phase evaluation framework** integrating realistic scroll-based navigation, semantic and coordinate validation, and generalized prompting to assess how agents reason, act, and visually ground decisions in real-world browsing tasks.  
- Conducted extensive experiments on SOTA web agents across real-world sites, revealing that color saliency and geometric scaling strongly attract agents, while position shifts and blurred visuals lead to significant performance degradation.  
- Demonstrated that web agents exhibit human-like visual biases, such as favoring vivid colors, large targets, and central layouts, but remain brittle under degraded clarity and typography changes, underscoring the need for human-aligned and visually robust web agent design frameworks.  

---

### LyTimeT: Towards Robust and Interpretable State-Variable Discovery  
**Instructor**: [Hod Lipson (Columbia University)](https://www.hodlipson.com/)  
*Nov 2024 – Present*  
- Proposed **LyTimeT**, a hybrid video prediction framework that integrates a lightweight TimeSformer encoder-decoder with Lyapunov-based stability regularization to extract low-dimensional, interpretable dynamical variables from high-dimensional video.  
- Designed a compact TimeSformer by reducing embedding size and using spatial K-token pooling, while preserving temporal attention through a causal rollout mechanism to model long-term physical dynamics efficiently.  
- Introduced a **Lyapunov energy function** in latent space to penalize unstable rollouts, encouraging convergence to physically plausible trajectories over long horizons.  
- Validated LyTimeT on diverse synthetic and real video datasets (e.g., pendulums, lava lamp, fire), demonstrating superior stability, interpretability, and predictive accuracy compared to prior state-variable extraction methods.  

---

### [Submitted to ICCV 2025] POLAR: Policy-based Layerwise Reinforcement Method for Stealthy Backdoor Attacks in Federated Learning  
**Instructors**: [Hao Wang (Stevens Institute of Technology)](https://intellisys.haow.us/haowang/), Yang Hua (Queen’s University Belfast), Tao Song (Shanghai Jiao Tong University)  
*July 2024 – March 2025*  
- Proposed **POLAR**, the first reinforcement learning (RL) framework for backdoor attacks in federated learning (FL), which formulates layer selection as an RL problem to identify the most effective attack layers.  
- Designed POLAR by combining reinforcement learning with layerwise poisoning attack, which adapts dynamically during training using real-time feedback on backdoor success rate (BSR) and optimizes the stealth–performance tradeoff under FL defenses.  
- Demonstrated that POLAR outperforms LP Attack and BadNets in BSR, main task accuracy, and malicious client acceptance rate (MAR) across diverse settings and state-of-the-art defense mechanisms.  

---

### Contribution Feedback Aggregation Algorithm in Federated Learning  
**Instructors**: Tao Song, Ke Xu (Shanghai Jiao Tong University)  
*Jan 2024 – May 2024*  
- Developed a novel explainable aggregation algorithm that integrates feedback from incentive mechanisms to support robust and fair FL aggregation.  
- Mitigated the negative impact of low-quality participants by feeding contribution evaluation results back into traditional aggregation processes.  
- Demonstrated faster convergence and higher accuracy in large-scale or low-quality-user-dominated federated training environments.  

---

### W3FedPOSE: A Practical WEB3.0-Based Federated Learning Framework  
**Instructors**: [Bingsheng He (National University of Singapore)](https://www.comp.nus.edu.sg/~hebs/), Yang Hua (Queen’s University Belfast), Tao Song (Shanghai Jiao Tong University)  
*April 2023 – Oct 2023*  
- Proposed **FedTreeSHAP**, an innovative linear-time Shapley approximation algorithm to efficiently and fairly measure participant contributions in a Web3.0-based federated learning framework.  
- Reduced computational complexity from \(O(2^n)\) to \(O(n)\) using a tree computation structure, enabling scalable and fair contribution allocation.  
- Validated the algorithm on multiple benchmarks, outperforming other approximations in accuracy while maintaining the same order of computational cost.  

Awards
======
- **Leading Cyber Security Scholarship** — *Top 5%*, awarded based on comprehensive performance  
  *2023*

- **Zhiyuan Honour Scholarship** — *Top 5%*, awarded based on academic excellence  
  *2020, 2021*
