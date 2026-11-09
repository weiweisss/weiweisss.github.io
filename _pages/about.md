---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

She Yifei is a Ph.D. candidate in Artificial Intelligence at Beijing University of Posts and Telecommunications (BUPT), supervised by Prof. Kai Niu. He received his B.Eng. in Communication Engineering from BUPT in 2026. His doctoral research focuses on the interpretability of Large Language Models (LLMs) through the lens of semantic information theory.

His research interest includes semantic information theory, mechanistic interpretability and representation learning.


# 📝 Publications 
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Entropy 2026</div>
      <img src='images/1entropy26.png' alt="1entropy26" width="100%">
    </div>
  </div>
  
  <div class='paper-box-text' markdown="1">
    
  Semantic Algorithmic Information Theory: From Kolmogorov Complexity to Semantic Equivalence

  Jiatong Wu, Sen Wang, Kai Niu, **Yifei She**, Ping Zhang

  [**Paper**](https://www.mdpi.com/1099-4300/28/5/554)
  - We introduce Semantic Algorithmic Information Theory, formalize the Semantic Turing Machine System, define Semantic Complexity, and propose a model-based estimator of Normalized Semantic Information Distance to measure semantic equivalence beyond syntactic variation.
  </div>
</div>
<br>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">arXiv</div> 
      <img src='images/2arxiv26.png' alt="2arxiv26" width="100%">
    </div>
  </div>
  
  <div class='paper-box-text' markdown="1">
    
  Learning to Wait: Synchronizing Agents with the Physical World

  **Yifei She**, Ping Zhang, He Liu, Yanmin Jia, Yang Jing, Zijun Liu, Peng Sun, Xiangbin Li, Xiaohe Hu

  [**Paper**](https://arxiv.org/abs/2512.16262)
  - We leverage the semantic priors of LLMs to endow them with the ability to actively wait for event completion, thereby reducing the manual effort required for system-side development.
  </div>
</div>
<br>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">EMNLP 2025</div>
      <img src='images/1emnlp25.png' alt="emnlp25" width="100%">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">

  DisLoRA: Task-specific Low-Rank Adaptation via Orthogonal Basis from Singular Value Decomposition

  **She Yifei**, Xinhao Wei, Yulong Wang

  [**Paper**](https://aclanthology.org/2025.emnlp-main.694/)
  - We decompose LoRA's A and B matrices via SVD to identify task-specific directions for optimized training and use an adaptive soft regularization loss to accelerate convergence.
  </div>
</div>
<br>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ACC 2025</div>
      <img src='images/1acc25.png' alt="acc25" width="100%">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">

  Enhancing Vehicle Platooning Safety via Control Node Placement and Sizing under State and Input Bounds

  **Yifei She**, Shen Wang, Ahmad Taha, and Xiaofeng Tao

  [**Paper**](https://ieeexplore.ieee.org/abstract/document/11108044)
  - We utilize a greedy algorithm to select key control nodes and apply convex optimization to constrain over-approximated reachable sets, ensuring vehicle platooning safety.
  </div>
</div>


# 📖 Educations
- *2026.09 - Present*, Ph.D. Candidate in Artificial Intelligence, Beijing University of Posts and Telecommunications (BUPT). Supervised by Prof. Kai Niu, working on the interpretability of LLMs via semantic information theory.
- *2022.09 - 2026.06*, Bachelor of Engineering in Communication Engineering, Beijing University of Posts and Telecommunications (BUPT).

# 💻 Internships
- *2025.10 - 2026.11*, Research Intern at Infrawaves, working on production-grade AIOps and MaaS.
  - Explored agentic RL for incident handling; the problem of agents waiting on slow environments led to *Learning to Wait*.
  - Built InfraOps, an agent system deployed in real cluster operations, and presented it in an internal talk.
  - Helped bring Kimi K3 serving on GB300 from scratch to stable production with SGLang: tuned PD disaggregation ratios and parallelism, and fixed bugs.
  - Optimized prefill scheduling ([#26](https://github.com/Infrawaves/sglang/pull/26), [#75](https://github.com/Infrawaves/sglang/pull/75)) and multimodal peak memory ([#98](https://github.com/Infrawaves/sglang/pull/98)).
  - Improved the hierarchical KV cache: removed redundant per-rank MLA KV copies ([#72](https://github.com/Infrawaves/sglang/pull/72)), let decode write KV to Mooncake L3 for prefill to reuse ([#90](https://github.com/Infrawaves/sglang/pull/90)), and stabilized the L3 hit rate.

# 🎖 Awards and Experiences
- *2026.06*, College-level Outstanding Undergraduate Thesis, BUPT.
- *2025.11*, Granted a patent (CN121213699A) for synthesizing training images.
- *2025.10*, Third-Prize University Scholarship, BUPT.
- *2025.08*, Merged a Pull Request to PaddleNLP.
- *2025.08*, Outstanding Student, Financial Services Project, National University of Singapore (NUS) Summer Workshop.
- *2025.03*, Selected for BUPT's PING Program for advanced studies in Semantic Information Theory.
- *2024.11*, Recipient of the BUPT Future Scholars Research Fund.
- *2023.10*, Third-Prize University Scholarship, BUPT.
