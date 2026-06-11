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

Tong Guan is currently a Visiting PhD Student at the School of Information and Communication Technology, Griffith University (2024–present), where he is mentored by Dr [Ming Jin](https://mingjin.dev/) and Prof. [Shirui Pan](https://shiruipan.github.io/) in the [Trustworthy AGI (TrustAGI) Lab](https://trust-agi.github.io/), where his research focuses on multimodal time series analysis.

He is a PhD candidate in the College of Control Science and Engineering at Zhejiang University (2021–present), advised by Prof. [Jun Liang](http://www.cse.zju.edu.cn/2011/0225/c72511a2660323/page.htm). Prior to that, he received his B.Eng. from the College of Control Science and Engineering, Zhejiang University (2017–2021).

His research interests include multimodal learning, time series, and generative AI.

<!-- Citation count hidden until the Google Scholar stats crawler has populated data.
<a href='https://scholar.google.com/citations?user=Xgp-fIgAAAAJ&hl=zh-CN'>Google Scholar citations <strong><span id='total_cit'>0</span></strong></a> <a href='https://scholar.google.com/citations?user=Xgp-fIgAAAAJ&hl=zh-CN'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.
-->


# 🔥 News
- *2026.06*: &nbsp;Serving as a Program Committee member for [MILETS Workshop @ KDD 2026](https://kdd-milets.github.io/milets2026/), Mining and Learning from Time Series, Jeju, South Korea.
- *2026.05*: &nbsp;🎉 Our latest preprint *AION: Next-Generation Tasks and Practical Harness for Time Series* is out on [arXiv](https://arxiv.org/abs/2605.25045). See the [project page](https://ztxtech.github.io/aion/).
- *2026.04*: &nbsp;*TimeOmni-VL: Unified Models for Time Series Understanding and Generation* accepted at ICML 2026. ![](https://img.shields.io/badge/CORE-A*-e74c3c) ![](https://img.shields.io/badge/CCF-A-e74c3c)
- *2026.01*: &nbsp;*TimeOmni-1: Incentivizing Complex Reasoning with Time Series in Large Language Models* accepted at ICLR 2026. ![](https://img.shields.io/badge/CORE-A*-e74c3c) ![](https://img.shields.io/badge/CCF-A-e74c3c)
- *2025.11*: &nbsp;Serving as a Program Committee member for [AI4TS Workshop @ AAAI 2026](https://ai4ts.github.io/aaai2026), AI for Time Series Analysis, Singapore.
- *2025.11*: &nbsp;Served as a Program Committee member for the [Workshop on Rethinking Financial Time-Series (RFTS) at ICAIF '25](https://icaif25-rfts.github.io/), Singapore.

# 📝 Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/paper/timeomni1-iclr-2026.png' alt="TimeOmni-1" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TimeOmni-1: Incentivizing Complex Reasoning with Time Series in Large Language Models](https://arxiv.org/abs/2509.24803)

<span style="color:#d6336c">**Tong Guan**</span>, Z. Meng, D. Li, S. Wang, C.-H. H. Yang, Q. Wen, Z. Liu, S. M. Siniscalchi, et al.

- Incentivizing complex reasoning with time series in large language models.

<a href="https://huggingface.co/collections/anton-hugging/timeomni-1-from-4b-to-9b"><img src="https://img.shields.io/badge/TimeOmni--1-Model-yellow?logo=huggingface&logoColor=white" alt="Model"></a>
<a href="https://huggingface.co/datasets/anton-hugging/timeomni-1-testbed"><img src="https://img.shields.io/badge/TimeOmni--1-Dataset-orange?logo=huggingface&logoColor=white" alt="Dataset"></a>
<a href="https://huggingface.co/spaces/anton-hugging/TimeOmni-1"><img src="https://img.shields.io/badge/TimeOmni--1-Demo-blue?logo=huggingface&logoColor=white" alt="Demo"></a>
<a href="https://github.com/AntonGuan/TimeOmni-1"><img src="https://img.shields.io/badge/TimeOmni--1-Inference%20Code-536af5?logo=github&logoColor=white" alt="Inference Code"></a>
<a href="/assets/videos/TimeOmni-1_Demo.mp4"><img src="https://img.shields.io/badge/TimeOmni--1-Demo%20Video-e74c3c?logo=youtube&logoColor=white" alt="Demo Video"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/paper/timeomnivl-icml-2026.png' alt="TimeOmni-VL" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TimeOmni-VL: Unified Models for Time Series Understanding and Generation](https://arxiv.org/abs/2602.17149)

<span style="color:#d6336c">**Tong Guan**</span>, S. Pan, J. Barthelemy, Z. Li, Y. Cai, C. Alippi, M. Jin, S. Pan

- Unified models for time series understanding and generation.

<a href="https://huggingface.co/TimeOmni-VL/TimeOmni-VL"><img src="https://img.shields.io/badge/TimeOmni--VL-Model-yellow?logo=huggingface&logoColor=white" alt="Model"></a>
<a href="https://huggingface.co/datasets/TimeOmni-VL/TSUMM-Suite_Training"><img src="https://img.shields.io/badge/TSUMM--Suite-Dataset-orange?logo=huggingface&logoColor=white" alt="Dataset"></a>
<a href="https://huggingface.co/spaces/anton-hugging/TimeOmni-VL"><img src="https://img.shields.io/badge/TimeOmni--VL-Demo-blue?logo=huggingface&logoColor=white" alt="Demo"></a>
<a href="https://github.com/AntonGuan/TimeOmni-VL"><img src="https://img.shields.io/badge/TimeOmni--VL-Code-536af5?logo=github&logoColor=white" alt="Code"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW WebST'25 Workshop</div><img src='images/paper/graphstage-2025.png' alt="GraphSTAGE" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GraphSTAGE: Channel-Preserving Graph Neural Networks for Time Series Forecasting](https://openreview.net/forum?id=5dKiZeF3MD)

<span style="color:#d6336c">**Tong Guan**</span>, K. Ma, J. Peng, J. Liang, B. Du, M. Jin, S. Pan

- Channel-preserving graph neural networks for time series forecasting.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ITSC 2023</div><img src='images/paper/stgmmoe-2023.png' alt="STGMMOE" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Spatial-Temporal Graph Multi-Gate Mixture-of-Expert Model for Traffic Prediction](https://ieeexplore.ieee.org/abstract/document/10422273)

<span style="color:#d6336c">**Tong Guan**</span>, J. Peng, J. Liang

- A spatial-temporal graph multi-gate mixture-of-expert model for traffic prediction.
</div>
</div>

### Other Publications
- [AION: Next-Generation Tasks and Practical Harness for Time Series](https://arxiv.org/abs/2605.25045). T. Zhan, X. Song, <span style="color:#d6336c">**Tong Guan**</span>, S. Pan, M. Jin. *arXiv:2605.25045*, 2026. [[Website]](https://ztxtech.github.io/aion/)
- Accurate Spatial Representation and Propagation Without Prior Knowledge for Traffic Forecasting. K. Ma, X. Yan, <span style="color:#d6336c">**Tong Guan**</span>, J. Peng, J. Liang. **CCC 2025**. ![](https://img.shields.io/badge/CAC-A-e74c3c)
- Trajectory Planning for Unmanned Surface Vessels in Confined Waters. Y. Zhan, J. Fan, <span style="color:#d6336c">**Tong Guan**</span>, J. Liang. **CAC 2024**. ![](https://img.shields.io/badge/CAC-A-e74c3c)
- An Optimal Trajectory Planning for Automated On-Ramp Merging. J. Liang, <span style="color:#d6336c">**Tong Guan**</span>, D. Liu, X. Liu, Z. Luan, H. Liu, X. Yuan. **IET Intelligent Transport Systems**, 17(5):835–847, 2023. ![](https://img.shields.io/badge/CAC-A-e74c3c)
- Spatial-Temporal Graph Discriminant AutoEncoder for Traffic Congestion Forecasting. J. Peng, <span style="color:#d6336c">**Tong Guan**</span>, J. Liang. **ITSC 2023**. ![](https://img.shields.io/badge/CAC-A-e74c3c)
- MND-GAN: A Research on Image Deblurring Algorithm Based on Generative Adversarial Network. J. Peng, <span style="color:#d6336c">**Tong Guan**</span>, F. Liu, J. Liang. **CCC 2023**. ![](https://img.shields.io/badge/CAC-A-e74c3c)
- A Bipartite Graph Based Method for Traffic Continuous Data Imputation. J. Peng, <span style="color:#d6336c">**Tong Guan**</span>, J. Liang. **CAC 2023**. ![](https://img.shields.io/badge/CAC-A-e74c3c)

# 📖 Educations
- *2021.09 - present*, PhD candidate, College of Control Science and Engineering, Zhejiang University.
- *2024 - present*, Visiting PhD Student, School of ICT, Griffith University.
- *2017.09 - 2021.06*, B.Eng., College of Control Science and Engineering, Zhejiang University.

# 🧑‍🏫 Academic Services

**💬 Conference Reviewer**

- [NeurIPS 2026](https://neurips.cc/Conferences/2026) — Conference on Neural Information Processing Systems, Sydney, Australia ![](https://img.shields.io/badge/CORE-A*-e74c3c) ![](https://img.shields.io/badge/CCF-A-e74c3c)

- [ICLR 2026](https://iclr.cc/Conferences/2026) — Int'l Conference on Learning Representations, Rio de Janeiro, Brazil ![](https://img.shields.io/badge/CORE-A*-e74c3c) ![](https://img.shields.io/badge/CCF-A-e74c3c)

- [ICLR 2025](https://iclr.cc/Conferences/2025) — Int'l Conference on Learning Representations, Singapore ![](https://img.shields.io/badge/CORE-A*-e74c3c) ![](https://img.shields.io/badge/CCF-A-e74c3c)

- [ICASSP 2026](https://2026.ieeeicassp.org/) — IEEE Int'l Conference on Acoustics, Speech and Signal Processing, Barcelona, Spain ![](https://img.shields.io/badge/CORE-B-e8821e) ![](https://img.shields.io/badge/CCF-B-e8821e)

**📄 Journal Reviewer**

- [ACM Transactions on Intelligent Systems and Technology (TIST)](https://dl.acm.org/journal/tist) — ACM ![](https://img.shields.io/badge/CCF-B-e8821e)

- [IEEE Transactions on Neural Networks and Learning Systems (TNNLS)](https://cis.ieee.org/publications/t-neural-networks-and-learning-systems) — IEEE ![](https://img.shields.io/badge/CCF-B-e8821e)

- [IEEE Transactions on Cognitive and Developmental Systems (TCDS)](https://cis.ieee.org/publications/t-cognitive-and-developmental-systems) — IEEE ![](https://img.shields.io/badge/CCF-C-2e8b57)

- [Neurocomputing](https://www.sciencedirect.com/journal/neurocomputing) — Elsevier ![](https://img.shields.io/badge/CCF-C-2e8b57)

- [IET Intelligent Transport Systems](https://ietresearch.onlinelibrary.wiley.com/journal/17519578) — IET

**🗒️ Program Committee**

- [MILETS Workshop @ KDD 2026](https://kdd-milets.github.io/milets2026/) — Mining and Learning from Time Series, Jeju, South Korea ![](https://img.shields.io/badge/CORE-A*-e74c3c) ![](https://img.shields.io/badge/CCF-A-e74c3c)

- [AI4TS Workshop @ AAAI 2026](https://ai4ts.github.io/aaai2026) — AI for Time Series Analysis, Singapore ![](https://img.shields.io/badge/CORE-A*-e74c3c) ![](https://img.shields.io/badge/CCF-A-e74c3c)

- [RFTS Workshop @ ICAIF 2025](https://icaif25-rfts.github.io/) — Rethinking Financial Time-Series, Singapore

<br>

<div style="width: 30%; margin: 0 auto; text-align: center;">
<!-- Visitor map (MapMyVisitors) -->
<script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=o0xcammCZ9U74V8GLO4ZQhMSrOjuaba23BywCTQ-q7Y&cl=ffffff&w=a"></script>
</div>
