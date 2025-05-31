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

Hi 👋, I'm **Peiyuan Zhu**, a first-year PhD student at <a href="https://mbzuai.ac.ae">MBZUAI</a>, majoring in **Machine Learning**, fortunately supervised by <a href="https://scholar.google.com/citations?user=RGoypN4AAAAJ&hl=en">Prof. Kun Zhang</a>.

My research interests center around **temporal explainability and controllability**, with a particular emphasis on leveraging **provable causal representations**. On the application side, I have developed representation learning methods for sequential data, including video, text, and trajectory.

If you share similar interests or want to discuss cool ideas, feel free to connect.

<!-- Optionally you can also add a News section or Publication section below -->
