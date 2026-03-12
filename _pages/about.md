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

I am a Ph.D. student in the School of Computer Science at Peking University, advised by Prof. Tao Xie. Before that, I received my B.S. (Honors) in Computer Science from Peking University in June 2025.

I am a member of PKUASE Group. My research interests lie in GUI agents, mobile/UI testing, and foundation models for software engineering. Recently, I have been working on scalable training pipelines for GUI agents, synthetic environment construction, reinforcement learning for multi-step decision making, and evaluation/benchmarking for real-world GUI tasks.

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

## News
- `2025.09` Started my Ph.D. at Peking University and joined the Turing Graduate Program.
- `2025` Our paper on cost-efficient GUI testing in industry was accepted to `ASE 2025`.
- `2023` Selected as a `CCF Outstanding Undergraduate`, one of two recipients from Peking University that year.

## Research Experience
- `2022.12 - Present` `PKUASE Group`, advised by Prof. Tao Xie.
  - Leading the design of an end-to-end training pipeline for GUI agents, spanning both mid-training and post-training.
  - Exploring multi-turn reinforcement learning, rejection sampling, unsupervised data scaling, and benchmark construction for GUI agents.
  - Developing LLM-based agents for software testing, automated test generation, and Android UI test migration across environments.
  - Participating in research on model merging and parameter-space understanding for large models.

## Selected Publications

Full list: [Google Scholar](https://scholar.google.com/citations?user=J0LIkIsAAAAJ) <img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations" alt="Google Scholar citations">

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->
- `UI-Oceanus: Scaling GUI Agents with Synthetic Environmental Dynamics.` **Mengzhou Wu**, Yuzhe Guo, Yuan Cao, Haochuan Lu, et al. `ICML 2026`, under review.
- `Element-Aware Fine-Tuning of Vision-Language Models for Cost-Efficient GUI Testing in an Industrial Setting.` **Mengzhou Wu**\*, Yuzhe Guo\*, Yuan Cao, Haochuan Lu, et al. `ASE 2025`.
- `SAIL: LLM-based Android UI Test Migration with Skill-Adaptive Imitation Learning.` **Mengzhou Wu**, Hao Wang, Jun Ren, Yuan Cao, et al. `arXiv`.
- `Beyond Pass or Fail: A Multi-Dimensional Benchmark for Mobile UI Navigation.` Dezhi Ran\*, **Mengzhou Wu**\*, Hao Yu, Yuetong Li, et al. `TOSEM`, under review.
- `Foundation Model Engineering: Engineering Foundation Models Just as Engineering Software.` Dezhi Ran, **Mengzhou Wu**, Wei Yang, Tao Xie. `TOSEM`.

## Honors and Awards
<!-- - *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
- `2025` Selected for the `Turing Graduate Program`, Peking University.
- `2023` `CCF Outstanding Undergraduate`, one of two recipients from Peking University.
- `2022` `CCPC Mianyang` Gold Medal, `Rank 3`.
- `2022 - 2023` Multiple `ICPC` regional Gold Medals, including Xi'an, Jinan, and Kunming.
- `2020` `NOI Gold Medal` and admission to Peking University through the National Training Team.
- `2021 - 2024` Multiple university honors and scholarships, including the Huawei Scholarship, SZSE Scholarship, and Suzhou Industrial Park Scholarship.


## Education
<!-- - *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
- `2025.09 - Present` Ph.D. student in Computer Science, Peking University, advised by Prof. Tao Xie.
- `2021.09 - 2025.06` B.S. (Honors) in Computer Science, Turing Class, Peking University. GPA `3.75/4.0`, top `10%`.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

## Competitive Programming
- `2018 - Present` Active in `NOI`, `ICPC`, and `CCPC`.
- Gold medalist at `NOI 2020`, ranked in the national top 50 and selected into the National Training Team.
- `CCPC 2022 Mianyang` Rank 3, `CCPC 2021 Harbin` Rank 3, with multiple ICPC/CCPC regional Gold Medals.
- Served as a problem setter for several programming contests.
