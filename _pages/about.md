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

# Welcome to Peiyuan's Homepage!

Hi 👋, I'm Peiyuan Zhu (/ˈpeɪ.jwæn zuː/), a first-year PhD student in Machine Learning Department at <a href="https://mbzuai.ac.ae">MBZUAI</a>, fortunately supervised by <a href="https://scholar.google.com/citations?user=RGoypN4AAAAJ&hl=en">Prof. Kun Zhang</a>. My email address is peiyuan [dot] zhu [at] mbzuai [dot] ac [dot] ae.

## Research

My research interests lie at the intersection of Computer Vision, Machine Learning, and Trustworthy AI, with a particular emphasis on temporal **explainability** and **controllability** with provable **causal representations**. On the application side, I have developed representation learning methods for sequential data, including video, text, and trajectory.

I am currently interested in **any-time controllable video generation/editing**, with the goal of understanding and controlling the latent cognitive processes in a principled way.

If you share similar interests or want to discuss cool ideas, feel free to connect.

## Publications 

<div class='paper-box'><div class='paper-box-image'><div><img src='images/causalverse.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  [**CausalVerse: Benchmarking Causal Representation Learning with Configurable High-Fidelity Simulations**](https://arxiv.org/abs/2502.13759) ![Static Badge](https://img.shields.io/badge/NeurIPS2025-submission-green)
 
 Guangyi Chen, Yunlong Deng, **Peiyuan Zhu**, Yan Li, Yifan Shen, Zijian Li, Kun Zhang
 
*"CausalVerse is a high-fidelity visual benchmark for Causal Representation Learning, offering ground-truth causal structures across diverse static and dynamic scenarios to enable rigorous and realistic evaluation of CRL methods."* 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/covogan.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  [**Controllable Video Generation with Provable Disentanglement**](https://arxiv.org/abs/2502.13759) ![Static Badge](https://img.shields.io/badge/NeurIPS2025-submission-green)
 
 Yifan Shen\*, **Peiyuan Zhu\***, Zijian Li, Shaoan Xie, Zeyu Tang, Namrata Deka, Zongfang Liu, Guangyi Chen, Kun Zhang
 
 (\*: first co-authors)

*"CoVoGAN is a controllable video generation framework that disentangles static and dynamic concepts for independent control, achieving superior quality and controllability through theoretically grounded latent dynamics modeling."* 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/dmpred.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
 [**Attentive Radiate Graph for Pedestrian Trajectory Prediction in Disconnected Manifolds**](https://ieeexplore.ieee.org/abstract/document/10962257) ![Static Badge](https://img.shields.io/badge/TITS-red)
 
 **Peiyuan Zhu**, Shengjie Zhao, Hao Deng, Fengxia Han 

*"The problem of multimodal pedestrian prediction in disconnected manifolds is considered. A graph-based generative method that incorporates the localized influence radiating from pedestrian movements is proposed and implemented on GPU. Experimental results show that the model achieves state-of-the-art accuracy in distance-based metrics while effectively reducing out-of-distribution samples."*
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/beavp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  [**BEAVP: A Bidirectional Enhanced Adversarial Model for Video Prediction**](https://ieeexplore.ieee.org/abstract/document/10581919) ![Static Badge](https://img.shields.io/badge/FG'2024-red)
  
  **Peiyuan Zhu**, Shengjie Zhao, Fengxia Han, Hao Deng

*"BEAVP, a stochastic video prediction model based on coupled GANs, leverages cycle-consistency and shared latent space to capture spacetime-varying motion patterns, achieving state-of-the-art results on video prediction benchmarks."* 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/multi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[**Flexible Multi-generator Model with Fused Spatiotemporal Graph for Trajectory Prediction**](https://ieeexplore.ieee.org/abstract/document/10562932) ![Static Badge](https://img.shields.io/badge/Radar'2023-red)

**Peiyuan Zhu**, Fengxia Han, Hao Deng

*"A multi-generator trajectory prediction framework using a fused spatiotemporal graph to model complex pedestrian interactions"*
</div>
</div>

## Experiences

Prior to joining <a href="https://mbzuai.ac.ae">MBZUAI</a>, I obtained my B.Eng. and M.Eng. degrees in Computer Science and Technology from <a href="https://www.tongji.edu.cn">Tongji</a>, supervised by <a href="https://scholar.google.com/citations?user=N2xsxV8AAAAJ&hl=en">Prof. Jihong Guan</a> (2017–2021), <a href="https://ieeexplore.ieee.org/author/37085508115">Prof. Shengjie Zhao</a>, and <a href="https://ieeexplore.ieee.org/author/37086691124">Prof. Hao Deng</a> (2021–2024). I also conducted research as a visiting student at <a href="https://en.sjtu.edu.cn">SJTU</a>, working with <a href="https://scholar.google.com/citations?user=NGQrfUwAAAAJ&hl=zh-CN">Prof. Cailian Chen</a>. Additionally, I completed an industry internship at Huawei's Kunpeng Cloud Division.

## Services

Served as a journal reviewer for the IEEE Transactions on Intelligent Transportation Systems (TITS) and the IEEE Transactions on Geoscience and Remote Sensing (TGRS).
