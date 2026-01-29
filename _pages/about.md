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
{% assign gsDataBaseUrl = "<https://cdn.jsdelivr.net/gh/>" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "<https://raw.githubusercontent.com/>" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi! I am Shigeng Wang (王世耿), a Ph.D. student in Computer Science at Beijing University of Posts and Telecommunications (BUPT), supervised by <a href='https://teacher.bupt.edu.cn/ouzhonghong/zh_CN/'>Zhonghong Ou</a>. I obtained my Bachelor’s degree from BUPT and continued my Ph.D. studies at BUPT through the direct doctoral track, with an expected graduation in June 2026.

I am currently conducting research at Intel Labs China <img src='images/intel.jpg' style='width: 2.5em;'> as an AI Research Intern, supervised by <a href='https://yaoanbang.github.io/'>Anbang Yao</a>. My research focuses on large language model quantization, compression, and hardware-efficient acceleration. More broadly, my interests lie in computer vision and efficient deep learning, with particular emphasis on model quantization and lightweight inference.

# 🔥 News

- *2026.01*: A first-author paper (SliderQuant) on post-training quantization for large language models was accepted to **ICLR 2026**.
- *2026.01*: Three first-author papers were accepted to **ICASSP 2026**.
- *2025.11*: The <a href='https://cherry.pcelves.com/'>Yingtao App</a>, an AI PC intelligent assistant powered by SliderQuant, was released by Intel, with me as a core developer.
- *2023.01*: A co-authored paper on machine learning for fungal keratitis diagnosis was accepted to **eBioMedicine**.
- *2022.11*: Contributed to the development of <a href='https://github.com/OpenPPL/ppq_tools'>ppq_tools</a>, a user-friendly model quantization toolkit.
- *2021.10*: A first-author paper on lightweight object detection was accepted to **CCIS 2021**.

# 📝 Publications

(* Equal contribution, # Corresponding author)

## Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/sliderquant.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SliderQuant: Accurate Post-Training Quantization for Large Language Models](https://openreview.net/pdf?id=YNqZqw4fLT)

**Shigeng Wang\***, Chao Li\*, Yangyuxuan Kang, Jiawei Fan, Zhonghong Ou, Anbang Yao#.  

<!-- [**Code**](https://github.com/deep-optimization/ScaleKD) **|** [**Project**](https://deep-optimization.github.io/scalekd/) -->
[**Code**](#) **|** [**Project**](#) *(to be released)*

SliderQuant is a post-training quantization framework that adaptively accounts for layer-wise sensitivity in large language models, achieving strong performance gains under ultra-low-bit weight and weight-activation quantization.

</div>
</div>

- [Dynabits: Token-Aware Weight–Activation Quantization for Large Vision–Language Models](#), **Shigeng Wang**, Zhonghong Ou#, Hongxing Zhang, IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP 2026).
- [VARDet: Visual Autoregressive Multi-Scale Prediction and CLIP-Guided Semantics for UAV Small-Object Detection](#), **Shigeng Wang**, Zhonghong Ou#, Hongxing Zhang, IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP 2026).
- [Foreground-Enhanced Coarse-to-Fine Detection for UAV Small Objects](#), **Shigeng Wang**, Zhonghong Ou#, Hongxing Zhang, IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP 2026).
- [Development and Multi-Center Validation of a Machine Learning Model for Early Detection of Fungal Keratitis](https://www.thelancet.com/journals/ebiom/article/PIIS2352-3964(23)00003-8/fulltext), Zhenyu Wei, **Shigeng Wang**, Zhiqun Wang, et al., eBioMedicine, 2023.

- [PowerDet: Efficient and Lightweight Object Detection for Electric Power Open Scenes](https://ieeexplore.ieee.org/document/9754678), **Shigeng Wang**, Zhonghong Ou#, Meina Song, IEEE 7th International Conference on Cloud Computing and Intelligent Systems (CCIS 2021).

# 📖 Educations

- *2021.09 – 2026.06*, Ph.D. student in Computer Science, Beijing University of Posts and Telecommunications (BUPT).

- *2017.09 – 2021.06*, B.Eng. in Data Science and Big Data Technology, Beijing University of Posts and Telecommunications (BUPT).

# 🎖 Honors and Awards

- *2023.07*: BUPT Excellent Ph.D. Students Foundation.
- *2022.10*: First-Class Scholarship, Beijing University of Posts and Telecommunications.  
- *2022.06*: BUPT Excellent Ph.D. Students Foundation.  
- *2021.06*: Outstanding Graduate of Beijing Municipality.  
- *2020.09*: First Prize, National College Student Mathematics Competition.  
- *2020.07*: First Prize, National College Student E-Commerce “Innovation, Creation, Entrepreneurship” Challenge.  
- *2019.09*: Second Prize, China Undergraduate Mathematical Contest in Modeling.  
- *2018.10*: National Encouragement Scholarship.

# 💬 Academic service

Reviewer:  ICML 2026, PRCV 2025.

<!-- - *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Experieces

- *2024.04 - now*, Intel Labs, China. <img src='images/intel.jpg' style='width: 2.5em;'> Researcher Intern, supervised by Anbang Yao.
- *2023.10 – 2024.03*, QCraft, China. <img src='images/qcraft_2.jpeg' style='width: 3.3em;'> Research Intern, focusing on autonomous driving perception.
