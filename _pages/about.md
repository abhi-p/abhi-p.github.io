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

 Hi there! I am Data Scientist/ML Engineer with over four years of experience working with cross-functional teams in building systems that leverage data to deliver tailored solutions into production. Self-motivated and lifelong learner capable of building end-to-end ETL pipelines and ML systems.
 
 I've had some great experiences working at Rogers Communications as a Senior Data Scientist, where I built cool tools like JARVIS (a RAG chatbot that leverages Meta's Lamma3 in order to query databases and retrive data), forecasting models, sentiment analyis social media montering tools. 
 
 While working I wanted to know more about NLP fundamentals and by Fall 2022 I started my Masters of CS at UT Austin to sharpen skills and am set to graduate in June 2024. Before this I graduated with a Bachelor’s in Computer Engineering from the University of Toronto.

*In case the information on this website gets out of date, I last updated it on May 21st, 2024

**Projects**
======
<i class="fas fa-link" aria-hidden="true"></i>  <a href="https://abhi-p.github.io/projects/">Details and Contribution</a>
<ul>{% for post in site.projects reversed %}
  {% include archive-single-short-project.html %}
{% endfor %}</ul>