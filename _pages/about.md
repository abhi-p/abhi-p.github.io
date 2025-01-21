---
permalink: /
title: "Home"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<!-- ![Profile Picture](images/profile-4-resized.jpg) -->
<div style="text-align: center;">
  <img src="images/profile-4-resized.jpg" alt="Profile Picture" style="max-width: 100%; height: auto;">
</div>
**Summary:**

Machine Learning Engineer with over 5 years of experience designing and deploying large-scale, high-performance machine learning systems. Proficient in Python, Go, and C++, with expertise in open-source ML frameworks (TensorFlow, PyTorch). Experienced in building and maintaining end-to-end ML pipelines, real-time anomaly detection, and forecasting models. Skilled at collaborating with researchers and stakeholders to develop scalable systems that solve complex problems.

*In case the information on this website gets out of date, I last updated it on May 21st, 2024

**Projects**
======
<i class="fas fa-link" aria-hidden="true"></i>  <a href="https://abhi-p.github.io/projects/">Details and Contribution</a>
<ul>{% for post in site.projects reversed %}
  {% include archive-single-short-project.html %}
{% endfor %}</ul>