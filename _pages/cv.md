---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Bachelors of Applied Science and Engineering (Computer Engineering), University of Toronto, 2020
  * GPA: 3.74 on 4.0

* M.S. in Computer Science, The University of Texas at Austin (expected Dec 2024)
  * GPA: 3.91 out of 4.0 ([Transcript](https://abhi-p.github.io/files/Abhishek_Paul_University_of_Texas_Unofficial_Transcripts.pdf))


Work experience
======

* **May 2022 - present: Senior Data Scientist, Rogers Communications**
  * Spearheaded the development of a RAG (Retrieval Augmented Generation) pipeline, utilizing the Haystack framework with Lamma 3 as the LLM model. The model would convert user questions into SQL queries and return the result. Empowered executives and non-technical teams, to effortlessly "query" network KPIs from the database.
  * Developed a real-time network disruption identification tool. Collaborated with network engineering teams to identify problematic network patterns and then trained a Seasonal decomposition (STL) detection model to swiftly identify these patterns in live data. Decreased detection lead time from hours to minutes, enabling quick alerting and preemptive issue resolution and ensuring uninterrupted service for customers
  * Leveraged crowd-sourced customer usage data, network KPIs, and geospatial data to train an ML-based (Random Forest) tower coverage model. Utilized by national planning to evaluate locations for new towers. Automated and optimized many aspects of network planning, reducing Capex by over $400 million.
  * Spearheaded the development of a forecasting model leveraging Meta's Prophet to predict network traffic growth, integrating considerations for seasonality and the influence of public events on abnormal network traffic.
  * Designed a comprehensive and intuitive KPI dashboard utilizing Grafana to monitor ongoing Rogers 5G deployment in the TTC (Toronto Transit) subway system. Used extensively by senior leadership, planning teams, and external stakeholders, this dashboard was pivotal in the deployment of cellphone coverage in less than 4 months. 
  * Utilized customer connectivity data to provide customer journey analytics, station congestion, and other dashboards and analytics to TTC. This was part of a pioneering initiative to leverage customer connectivity data to collaborate with municipalities and improve municipal services planning


* **June 2021 - April 2022: Data Scientist, Rogers Communications**
  * Led a 911 criticality study using crowdsource data and network KPIs to identify critical sites whose coverage areas have no backup from any network operators. Used in assigning criticality to sites to ensure no area loses 911 connectivity.
  * Determined appropriate techniques, models, and extensions to analyze geospatial data using GeoPandas, Shapely, PyKML, MongoDB, PostGIS, and various SQL functions.
  * Developed a tool that utilized a Random Forest Classifier on network quality data to detect and flag degradation in customer performance in real time, reducing response times by over 78%
  * Proactively refactored and enhanced the performance of ETL pipelines through the implementation of intelligent partitioning and indexing. Achieved a 64% reduction in run time.
  * Integrated terabytes of crowd-source customer and geospatial data from multiple sources at different h3 hexagon resolutions. This data was then visualized in an interactive web interface allowing planners to drill down to a 65 m resolution.
  *  Provided mentorship to new team members through pairing sessions, providing an understanding of the internal data stacks, and methodologies.
  *  Led a team of 3 to migrate multiple on-prem processes onto the Azure cloud environment. 



* **June 2020 - June 2021: Software Developer, Rogers Communications**
  * Provided metrics for API usage for stakeholders and performed ad-hoc analysis for the app ecosystem using SQL (Presto query
language), Jupyter Notebooks (Pandas, SciKit Learn, and Facebook’s AI libraries) to support ongoing projects in the
Partner-facing product areas.
  * Developed automation tool for nationwide audit of network parameters. Utilized by all regional teams and reduced OPEX costs by $465 thousand/year and avoided a Capex of $1.3 M. 
  * Conducted feature analysis on customer data to identify key causes of churn. Developed a random forest classifier to classify high churn-risk customers for retention marketing.
  * Analyzed large sets of data (Python, Pandas, SQLAlchemy, PyMango, and MariaDB), developing machine learning models (Python, PySpark, AzureML, MLflow), and creating complex dashboards (PowerBI and Grafana). 


* **May 2018 - May 2019: Software Development Engineer Intern, AMD.**
    * Developed of a comprehensive testing and verification framework enabling engineers to validate functionality pre-integration, ensuring seamless deployment to the main chip.
    * Synthesis, timing closure, and formal verification on the block and/or chip level using state-of-the-art CAD tools.
  
Skills
======
* Programming Languages
  * Python, C++, Java, JavaScript, SQL

Tools
======
* Data:
  * Pandas,  Hadoop, NumPy, Dask, Hugging Face Transeformers
* Software Development:
  * Git, Docker, Conda, Streamlit, Flask, JUnit, unittest.
* Cloud: 
  * AWS, Azure cloud services


Projects
======
<i class="fas fa-link" aria-hidden="true"></i>  <a href="https://abhi-p.github.io/projects/">Details and Contribution</a>
<ul>{% for post in site.projects reversed %}
  {% include archive-single-short-project.html %}
{% endfor %}</ul>


