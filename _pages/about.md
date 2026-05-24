---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
html {
  scroll-behavior: smooth;
}

.section-title {
  position: relative;
  scroll-margin-top: 90px;
  box-sizing: border-box;

  display: flex !important;
  align-items: center !important;

  min-height: 44px;
  padding: 0 12px !important;
  margin-top: 1.2rem !important;
  margin-bottom: 0.6rem !important;

  line-height: 1.1 !important;
  border-radius: 6px;
  transition: background-color 0.25s ease, box-shadow 0.25s ease;
}

.section-title.nav-highlight {
  background-color: #fff3b0 !important;
  box-shadow: 0 0 0 2px rgba(255, 200, 0, 0.45);
}

.section-title.nav-highlight::before {
  content: "";
  position: absolute;
  left: -70px;
  top: 50%;
  margin-top: 2px;
  width: 60px;
  height: 60px;
  background-image: url("{{ '/images/Point.jpg' | relative_url }}");
  background-size: contain;
  background-repeat: no-repeat;
  background-position: center;
  z-index: 10;
  transform: translateY(-50%);
  animation: point-bounce-img 0.9s ease-in-out 3;
}

@keyframes point-bounce-img {
  0% {
    transform: translateY(-50%) translateX(-8px);
    opacity: 0;
  }
  30% {
    transform: translateY(-50%) translateX(0);
    opacity: 1;
  }
  60% {
    transform: translateY(-50%) translateX(-5px);
    opacity: 1;
  }
  100% {
    transform: translateY(-50%) translateX(0);
    opacity: 1;
  }
}

.venue {
  color: #0033cc;
  font-weight: 700;
}

.pub-link {
  color: #2c7fb8;
  font-weight: 400;
}

.pub-note {
  font-size: 0.85em;
  color: #555;
  margin-top: -0.3rem;
  margin-bottom: 0.8rem;
}
  
</style>


{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<h2 id="about-me" class="section-title">About Me</h2>

I am a Ph.D. student at SKKU (Sungkyunkwan University), South Korea, advised by Prof. [Sungeun Hong](https://www.csehong.com/) in the [AI & Media Lab (AIM Lab)](https://aim.skku.edu/home). My research interests include vision-language models, multimodal learning, visual token pruning, and test-time adaptation.


<h1 id="news" class="section-title">🔥 News</h1>
- *2026.02*: &nbsp;🎉🎉 One paper is accepted to CVPR 2026. 
- *2025.09*: &nbsp;🎉🎉 One paper is accepted to NeurIPS 2025.
- *2025.06*: &nbsp;🎉🎉 One paper is accepted to IJCV 2025 (Q1, JCR: Top 10%).


<h1 id="publications" class="section-title">📝 Publications</h1>

<p class="pub-note"><sup>*</sup> Equal contribution. <sup>†</sup> Corresponding author.</p>

- **ZOO-Prune: Training-Free Token Pruning via Zeroth-Order Gradient Estimation in Vision-Language Models**
  - Youngeun Kim<sup>*</sup>, Youjia Zhang<sup>*</sup>, **Huiling Liu**, Aecheon Jung, Sunwoo Lee, and Sungeun Hong<sup>†</sup>
  - <span class="venue">CVPR 2026</span> [<a class="pub-link" href="https://aim-skku.github.io/ZOO-Prune/">Project page</a>]

- **Backpropagation-Free Test-Time Adaptation via Probabilistic Gaussian Alignment**
  - Youjia Zhang, Youngeun Kim, Young-Geun Choi, Hongyeob Kim, **Huiling Liu**, and Sungeun Hong<sup>†</sup>
  - <span class="venue">NeurIPS 2025</span> [<a class="pub-link" href="https://aim-skku.github.io/ADAPT/">Project page</a>]

- **CAT-TPT: Class-Agnostic Text-based Test-time Prompt Tuning for Vision-Language Models**
  - Youjia Zhang, **Huiling Liu**, Youngeun Kim, and Sungeun Hong<sup>†</sup>
  - <span class="venue">IJCV 2025</span> [Q1, JCR Top 3%, IF 11.6] [<a class="pub-link" href="https://link.springer.com/article/10.1007/s11263-025-02508-1">DOI</a>]




<h1 id="projects" class="section-title">📁 Projects</h1>
- ### Visuo-Tactile World Model for Dexterous Robotic Manipulation with Non-Standard Sensors (2026.03 – Present)  
  - Funded by the National Research Foundation of Korea
  - This project studies a world model-based robotic manipulation framework that integrates visual and tactile information under non-standard tactile sensor environments. It focuses on sensor-invariant tactile representation learning and visuo-tactile sim-to-real transfer for stable and precise robotic manipulation across diverse sensors and environments.

- ### Human-oriented AI Model that Imitates the Human Growth Process based on Cognitive Science (2025.04 – 2025.12)  
  - Funded by the Institute for Information & Communications Technology Promotion (IITP)
  - This project aims to develop a human-oriented AI model that can understand and explain diverse physical phenomena and causal relationships through cognitive science-inspired learning mechanisms.


<h1 id="honors-and-awards" class="section-title">🎖️ Honors and Awards</h1>
- SKKU STEM Full Scholarship, 2024 – Present.
- IEIE Encouraging Paper Award, 2024.


<h1 id="patents" class="section-title">🪄 Patents</h1>
- Apparatus and Method for Prompt Tuning  ( U.S. Patent Application No. 19/545,275; Pending.)


<h1 id="academic-activities" class="section-title">💬 Academic Activities</h1>
- ### Reviewer
  - NeurIPS 2025
  - CVPR 2026

- ### Teaching Assistant
  - Advanced Machine Learning / Deep Learning, SKKU, Spring 2026.
  - Generative Deep Learning, SKKU, Fall 2025.
  - Introduction to Deep Learning, SKKU, Spring 2025.
  - Introduction to Deep Learning, SKKU, Fall 2024.


<h1 id="education" class="section-title">🎓 Education</h1>
- **Sungkyunkwan University**, South Korea, 2024.03 - Present 
  - Ph.D. Student, Department of Immersive Media Engineering
  - Advisor: Prof. [Sungeun Hong](https://www.csehong.com/)

- **Chongqing University of Technology**, China, 2020.09 - 2023.06 
  - M.S. in Information and Communication Engineering
  - Advisor: Prof. [Nan Xiang](https://scholar.google.com/citations?hl=en&user=i96jKnQAAAAJ&view_op=list_works&sortby=pubdate)

- **KAIST**, South Korea, 2022.03 - 2022.08
  - Visiting Student, [NICA Lab](https://nica.kaist.ac.kr/)


- **Suzhou University**, China, 2015.09 - 2019.06
  - B.Eng. in Communication Engineering


<script>
document.addEventListener("DOMContentLoaded", function () {
  function highlightSection(id) {
    if (!id) return;

    var target = document.getElementById(id.replace(/^#/, ""));
    if (!target) return;

    target.classList.remove("nav-highlight");
    void target.offsetWidth;
    target.classList.add("nav-highlight");

    setTimeout(function () {
      target.classList.remove("nav-highlight");
    }, 2600);
  }

  document.querySelectorAll('a[href^="/#"], a[href^="#"]').forEach(function (link) {
    link.addEventListener("click", function () {
      var href = link.getAttribute("href") || "";
      var hash = href.includes("#") ? href.substring(href.indexOf("#") + 1) : "";

      setTimeout(function () {
        highlightSection(hash);
      }, 120);
    });
  });

  if (window.location.hash) {
    setTimeout(function () {
      highlightSection(window.location.hash.substring(1));
    }, 300);
  }
});
</script>
