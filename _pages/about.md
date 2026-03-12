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
## About Me

I am Mengzhou Wu, a Ph.D. student in the School of Computer Science at Peking University and a member of PKUASE Group, advised by [Prof. Tao Xie](https://taoxiease.github.io/) and closely mentored by [Dezhi Ran](https://dezhi-ran.com/).

My research interests lie in GUI agents, and foundation models for software engineering. Recently, I have been working on scalable training pipelines for GUI agents, synthetic environment construction, multi-turn reinforcement learning, and evaluation benchmarks for real-world GUI tasks.

Before starting my Ph.D. in September 2025, I received my B.S. (Honors) in Computer Science from Peking University's Turing Class in June 2025.

<span class='anchor' id='news'></span>
## News

- 2026.01, Our paper *AppForge: From Assistant to Independent Developer -- Are GPTs Ready for Software Development?* was accepted to *ICLR 2026*.
- 2025.09, Our paper *Element-Aware Fine-Tuning of Vision-Language Models for Cost-Efficient GUI Testing in an Industrial Setting* was accepted to *ASE 2025*.
- 2025.09, Started my Ph.D. at Peking University and joined the Turing Graduate Program.

<span class='anchor' id='publications'></span>
## Publications

Full list: [Google Scholar](https://scholar.google.com/citations?user=J0LIkIsAAAAJ) <img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations" alt="Google Scholar citations">

<div class='paper-box'>
<div class='paper-box-image'>
  <div><img src='images/publications/ui-oceanus.png' alt="UI-Oceanus figure" width="100%"></div>
</div>
<div class='paper-box-text' markdown="1">

[UI-Oceanus: Scaling GUI Agents with Synthetic Environmental Dynamics](images/publications/uioceanus.pdf)

**Mengzhou Wu**, Yuzhe Guo, Yuan Cao, Haochuan Lu, dfshenzhu, Pingzhe Qu, Xin Chen, Kangqin, Zhongpu Wang, Xiaode Zhang, Xinyi Wang, Wei Dai, Gang Cao, Yuetang Deng, Gong Zhi, Dezhi Ran, Linyi Li, Wei Yang, Tao Xie

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'>
  <div><img src='images/publications/element-aware.png' alt="Element-Aware figure" width="100%"></div>
</div>
<div class='paper-box-text' markdown="1">

[Element-Aware Fine-Tuning of Vision-Language Models for Cost-Efficient GUI Testing in an Industrial Setting](https://ieeexplore.ieee.org/document/11334646)

**Mengzhou Wu**\*, Yuzhe Guo\*, Yuan Cao, Haochuan Lu, Hengyu Zhang, Xia Zeng, Liangchao Yao, Yuetang Deng, Dezhi Ran, Wei Yang, Tao Xie

*ASE 2025*

</div>
</div>

- **[Skill-Adaptive Imitation Learning for UI Test Reuse](https://arxiv.org/abs/2409.13311).** **Mengzhou Wu**, Hao Wang, Jun Ren, Yuan Cao, Yuetong Li, Alex Jiang, Dezhi Ran, Yitao Hu, Wei Yang, Tao Xie. *arXiv*.
- **[Beyond Pass or Fail: A Multi-Dimensional Benchmark for Mobile UI Navigation](https://arxiv.org/abs/2501.02863).** Dezhi Ran\*, **Mengzhou Wu**\*, Hao Yu, Yuetong Li, Jun Ren, Yuan Cao, Xia Zeng, Haochuan Lu, Zexin Xu, Mengqian Xu, Ting Su, Liangchao Yao, Ting Xiong, Wei Yang, Yuetang Deng, Assaf Marron, David Harel, Tao Xie. *arXiv*.
- **[Guardian: A Runtime Framework for LLM-Based UI Exploration](https://doi.org/10.1145/3650212.3680334).** Dezhi Ran, Hao Wang, Zihe Song, **Mengzhou Wu**, Yuan Cao, Ying Zhang, Wei Yang, Tao Xie. *Proceedings of the 33rd ACM SIGSOFT International Symposium on Software Testing and Analysis, 2024*.
- **[GUI-GENESIS: Automated Synthesis of Efficient Environments with Verifiable Rewards for GUI Agent Post-Training](https://arxiv.org/abs/2602.14093).** Yuan Cao, Dezhi Ran, **Mengzhou Wu**, Yuzhe Guo, Xin Chen, Ang Li, Gang Cao, Gong Zhi, Hao Yu, Linyi Li, Wei Yang, Tao Xie. *arXiv*.
- **[From User Interface to Agent Interface: Efficiency Optimization of UI Representations for LLM Agents](https://arxiv.org/abs/2512.13438).** Dezhi Ran, Zhi Gong, Yuzhe Guo, **Mengzhou Wu**, Yuan Cao, Haochuan Lu, Hengyu Zhang, Xia Zeng, Gang Cao, Liangchao Yao, Yuetang Deng, Wei Yang, Tao Xie. *arXiv*.
- **[Foundation Model Engineering: Engineering Foundation Models Just as Engineering Software](https://doi.org/10.1145/3719005).** Dezhi Ran, **Mengzhou Wu**, Wei Yang, Tao Xie. *ACM Transactions on Software Engineering and Methodology, 2025*.
- **[An Infrastructure Software Perspective toward Computation Offloading between Executable Specifications and Foundation Models](https://doi.org/10.1007/s11432-025-4311-9).** Dezhi Ran, **Mengzhou Wu**, Yuan Cao, Assaf Marron, David Harel, Tao Xie. *Science China Information Sciences, 2025*.
- **[AppForge: From Assistant to Independent Developer -- Are GPTs Ready for Software Development?](https://arxiv.org/abs/2510.07740).** Dezhi Ran, Yuan Cao, **Mengzhou Wu**, Simin Chen, Yuzhe Guo, Jun Ren, Zihe Song, Hao Yu, Jialei Wei, Linyi Li, Wei Yang, Baishakhi Ray, Tao Xie. *ICLR 2026*.
- **Trustworthy and Efficient Development of FM-Native Software via Computation Offloading with A Runtime System.** Dezhi Ran, Zihe Song, **Mengzhou Wu**, Yuan Cao, Wei Yang, Tao Xie. *FSE 2030 Software Engineering Roadmap Workshop*.
- **From Operations to Intents: Envisioning Application Software and Its Engineering in the Era of Foundation Models.** Dezhi Ran, Yuan Cao, **Mengzhou Wu**, Wei Yang, Tao Xie. *FSE 2030 Software Engineering Roadmap Workshop*.
- **[From User Operations to Agentic Automation: Toward Intent-Oriented Software in the LLM Era](https://jcst.ict.ac.cn/en/article/doi/10.1007/s11390-026-6182-0).** Tao Xie, Dezhi Ran, Yuan Cao, **Mengzhou Wu**, Yuzhe Guo, Wei Yang. *Journal of Computer Science and Technology*.
- **[An Empirical Study and Theoretical Explanation on Task-Level Model-Merging Collapse](https://openreview.net/forum?id=vBk8rBx06H).** Yuan Cao, Dezhi Ran, Yuzhe Guo, **Mengzhou Wu**, Simin Chen, Linyi Li, Wei Yang, Tao Xie. *OpenReview*.
- **[KernelBand: Boosting LLM-Based Kernel Optimization with a Hierarchical and Hardware-Aware Multi-Armed Bandit](https://arxiv.org/abs/2511.18868).** Dezhi Ran\*, Shuxiao Xie\*, Mingfang Ji, Ziyue Hua, **Mengzhou Wu**, Yuan Cao, Yuzhe Guo, Hao Yu, Linyi Li, Yitao Hu, Tao Xie. *arXiv*.
- **[Medusa: A Framework for Collaborative Development of Foundation Models with Automated Parameter Ownership Assignment](https://dl.acm.org/doi/10.1145/3729385).** Dezhi Ran, Yuan Cao, Yuzhe Guo, Yuetong Li, **Mengzhou Wu**, Simin Chen, Wei Yang, Tao Xie. *Proceedings of the ACM on Software Engineering, 2025*.

<span class='anchor' id='awards'></span>
## Awards

- 2023, CCF Outstanding Undergraduate, one of two recipients from Peking University.
- 2020, NOI Gold Medal and National Training Team.
- 2025, Turing Graduate Program, School of Computer Science, Peking University.
- 2022-2023, Gold medals at CCPC and ICPC regional contests, including CCPC Mianyang Rank 3, ICPC Xi'an, ICPC Jinan, and ICPC Kunming.
- 2024, Huawei Scholarship, Peking University.
- 2023, Suzhou Industrial Park Scholarship, Peking University.
- 2022, Shenzhen Stock Exchange Scholarship, Peking University.
- 2024, Meritorious Winner, Peking University.
- 2023, Meritorious Winner, Peking University.
- 2022, Academic Excellence Award, Peking University.
- 2021, Peking University Freshman Third-Class Scholarship.
- 2021, EECS Freshman Second-Class Scholarship.

<span class='anchor' id='services'></span>
## Services

- ICML 2026 reviewer.
- ACL 2025 co-reviewer.
- Programming Practice, TA, 2025-2026 Spring semester. A core required EECS course on object-oriented programming and algorithmic programming.
- Introduction to Computer Systems, TA for small class, 2024-2025 Fall semester. A core required course on computer systems for CS students.
- Algorithm Design and Analysis, TA for small class, 2023-2024 Spring semester. A core required EECS course on algorithms.
- Problem setter for several algorithm and programming contests(ICPC/CCPC).

<span class='anchor' id='work-experience'></span>
## Work Experience

- **Internship at Tencent, WeChat**, 2024.12-Present.
  - Led the Cost-Efficient GUI Testing in WeChat project, 2024.12-2025.06, which resulted in the paper *Element-Aware Fine-Tuning of Vision-Language Models for Cost-Efficient GUI Testing in an Industrial Setting*.
  - Led mid-training for the AI assistant for WeChat Mini Program, 2025.06-Present, which resulted in the paper *UI-Oceanus: Scaling GUI Agents with Synthetic Environmental Dynamics*.
