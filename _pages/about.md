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

Lianyu Hu is a 4th-year PhD candidate in Tianjin University, China, supervised by Prof [Wei Feng](https://scholar.google.com/citations?user=7ory1i8AAAAJ&hl=zh-CN&oi=ao). During his graduate student period, he worked closely with Prof [Shenglan Liu](https://scholar.google.com/citations?hl=zh-CN&user=MtbsE3YAAAAJ). His research interest includes Video Understanding, Sign Lnaguage Understanding and Multimodal Learning. 

# 🔥 News
- We release [**CorrNet+**](https://arxiv.org/abs/2404.11111), an unified model with superior performance on both **continuous sign language recognition** and **sign language translation** tasks by using **only RGB inputs**.
  
- We release [**AdaptSign**](https://arxiv.org/abs/2404.08226), a continuous sign language recognition (CSLR) model powered by frozen pretrained image models with **18.5%** & **18.8%** WER on phoenix2014, **18.6%** & **19.8%** WER on phoenix2014-T, **26.7%** & **26.3%** WER on CSL-Daily.

- We release [**DSTA-SLR**](https://arxiv.org/abs/2403.12519), which performs sign language recognition (SLR) with **pure skeleton inputs** but ahcieves comparable accuracy and much faster speed than recognition with RGB inputs.

# 📝 Publications 

## 📖 PrePrint
- [CorrNet+: Sign Language Recognition and Translation via Spatial-Temporal Correlation](https://arxiv.org/pdf/2404.11111.pdf), **Lianyu Hu**, Wei Feng, Liqing Gao, Zekang Liu, Liang Wan. 2024.04. [[code](https://github.com/hulianyuyy/CorrNet_Plus)].
  
- [Improving Continuous Sign Language Recognition with Adapted Image Models](https://arxiv.org/pdf/2404.08226.pdf), **Lianyu Hu**, Tongkai Shi, Liqing Gao, Zekang Liu, Wei Feng. 2024.04. [[code](https://github.com/hulianyuyy/AdaptSign)].

## 🖊️ Selected Publications
- Deep Correlated Prompting for Visual Recognition with Missing Modalities. **Lianyu Hu**, Tongkai Shi, Wei Feng, Fanhua Shang, Liang Wan. **<i>NeurIPS 2024</i>**. [[code](https://github.com/hulianyuyy/Deep_Correlated_Prompting)].
  
- Pose-Guided Fine-Grained Sign Language Video Generation. Tongkai Shi, **Lianyu Hu**, Fanhua Shang, Jichao Feng, Peidong Liu, Wei Feng. **<i>ECCV 2024</i>**. [[code](https://github.com/shitongkai/PGMM)].
  
- [Spatial Temporal Aggregation for Efficient Continuous Sign Language Recognition](https://ieeexplore.ieee.org/document/10488467). **Lianyu Hu**, Liqing Gao, Zekang Liu, Wei Feng. **<i>IEEE Transactions on Emerging Topics in Computational Intelligence</i>**.

- [Dynamic Spatial-Temporal Aggregation for Skeleton-Aware Sign Language Recognition](https://arxiv.org/pdf/2403.12519.pdf). **Lianyu Hu**, Liqing Gao, Zekang Liu, Wei Feng. **<i>COLING 2024</i>**. [[code](https://github.com/hulianyuyy/DSTA-SLR)]. 

- [COMMA: Co-Articulated Multi-Modal Learning](https://arxiv.org/pdf/2401.00268.pdf). **Lianyu Hu**, Liqing Gao, Zekang Liu, Chi-Man Pun, Wei Feng. **<i>AAAI 2024</i>**. [[code](https://github.com/hulianyuyy/COMMA)].

- [Scalable Frame Resolution for Efficient Continuous Sign Language Recognition](https://www.sciencedirect.com/science/article/pii/S0031320323006015). **Lianyu Hu**, Liqing Gao, Zekang Liu, Wei Feng. **<i>Pattern Recognition</i>**.

- [AdaBrowse: Adaptive Video Browser for Efficient Continuous Sign Language Recognition](https://arxiv.org/pdf/2308.08327.pdf). **Lianyu Hu**, Liqing Gao, Zekang Liu, Chi-Man Pun, Wei Feng. **<i>ACMMM 2023 (Oral)</i>**. [[code](https://github.com/hulianyuyy/AdaBrowse)].

- [Skeleton-Based Action Recognition with Local Dynamic Spatial-Temporal Aggregation](https://www.sciencedirect.com/science/article/abs/pii/S0957417423011855). **Lianyu Hu**, Shenglan Liu, Wei Feng. **<i>Expert Systems with Applications</i>**. [[code](https://github.com/hulianyuyy/STGAT)]. (Previous name: Spatial Temporal Graph Attention Network for Skeleton-Based Action Recognition)

- [Continuous Sign Language Recognition with Correlation Network](https://arxiv.org/pdf/2303.03202.pdf). **Lianyu Hu**, Liqing Gao, Zekang Liu, Wei Feng. **<i>CVPR 2023</i>**. [[code](https://github.com/hulianyuyy/CorrNet)].

- [Self-Emphasizing Network for Continuous Sign Language Recognition](https://arxiv.org/pdf/2211.17081.pdf). **Lianyu Hu**, Liqing Gao, Zekang Liu, Wei Feng. **<i>AAAI 2023 (Oral)</i>**. [[code](https://github.com/hulianyuyy/SEN_CSLR)].

- [Temporal Lift Pooling for Continuous Sign Language Recognition](https://arxiv.org/abs/2207.08734).**Lianyu Hu**, Liqing Gao, Zekang Liu, Wei Feng. **<i>ECCV 2022</i>**. [[code](https://github.com/hulianyuyy/Temporal-Lift-Pooling)].

- [HFNet: A Novel Model for Human Focused Sports Action Recognition](https://dl.acm.org/doi/pdf/10.1145/3422844.3423052).**Lianyu Hu**, Liqing Gao, Zekang Liu, Wei Feng. **<i>ACMMM 2020 Workshop</i>**.

# 🎖 Honors and Awards
- 2023.10, National Scholarship

# 📖 Educations
- *2021-now*, PhD candidate in Computer Science and Technology, Tianjin Univerisity
- *2018-2021*, MEng in Computer Science and Technology, Dalian University of Technology
- *2014-2018*, BSc in Electronics and Information Engineering, Dalian University of Technology

<!--

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCOLING 2024</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic Spatial-Temporal Aggregation for Skeleton-Aware Sign Language Recognition](https://arxiv.org/pdf/2403.12519.pdf)
[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />](https://github.com/hulianyuyy/DSTA-SLR)

**Lianyu Hu**, Liqing Gao, Zekang Liu, Wei Feng
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[COMMA: Co-Articulated Multi-Modal Learning](https://arxiv.org/pdf/2401.00268.pdf)
[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />](https://github.com/hulianyuyy/COMMA)

**Lianyu Hu**, Liqing Gao, Zekang Liu, Chi-Man Pun, Wei Feng

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Pattern Recognition</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Scalable Frame Resolution for Efficient Continuous Sign Language Recognition](https://www.sciencedirect.com/science/article/pii/S0031320323006015)

**Lianyu Hu**, Liqing Gao, Zekang Liu, Wei Feng
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMMM 2023 (Oral)</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AdaBrowse: Adaptive Video Browser for Efficient Continuous Sign Language Recognition](https://arxiv.org/pdf/2308.08327.pdf)
[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />](https://github.com/hulianyuyy/AdaBrowse)

**Lianyu Hu**, Liqing Gao, Zekang Liu, Chi-Man Pun, Wei Feng

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Expert Systems with Applications</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Skeleton-Based Action Recognition with Local Dynamic Spatial-Temporal Aggregation](https://www.sciencedirect.com/science/article/abs/pii/S0957417423011855)
[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />](https://github.com/hulianyuyy/STGAT)

**Lianyu Hu**, Shenglan Liu, Wei Feng
- Previous name: Spatial Temporal Graph Attention Network for Skeleton-Based Action Recognition

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Continuous Sign Language Recognition with Correlation Network](https://arxiv.org/pdf/2303.03202.pdf)
[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />](https://github.com/hulianyuyy/CorrNet)

**Lianyu Hu**, Liqing Gao, Zekang Liu, Wei Feng

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023 (Oral)</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Self-Emphasizing Network for Continuous Sign Language Recognition](https://arxiv.org/pdf/2211.17081.pdf)
[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />](https://github.com/hulianyuyy/SEN_CSLR)

**Lianyu Hu**, Liqing Gao, Zekang Liu, Wei Feng

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Temporal Lift Pooling for Continuous Sign Language Recognition](https://arxiv.org/abs/2207.08734)
[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />](https://github.com/hulianyuyy/Temporal-Lift-Pooling)

**Lianyu Hu**, Liqing Gao, Zekang Liu, Wei Feng

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMMM 2020 Workshop</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HFNet: A Novel Model for Human Focused Sports Action Recognition](https://dl.acm.org/doi/pdf/10.1145/3422844.3423052)

**Lianyu Hu**, Liqing Gao, Zekang Liu, Wei Feng
</div>
</div>

-->
