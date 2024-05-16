---
title: "Towards Fair Text Classification: Expert-Ensemble Debiasing in NLI"
collection: projects
urlslug: "ut-mscs-nlp-project"
type: "Academic"
permalink: /projects/2023-09-08-ut-mscs-nlp-project
contributors: "Abhishek Paul, Ayush Kumar"
contribution: "Formulated research question and GROK metric, wrote code to generate abstractive summaries and ran experiments to train hundreds of BiLSTM models on AWS GPUs."
date: 2023-09-08
teaserurl: 'nlp_project_figures.png'
reporturl: 'https://abhi-p.github.io/files/Towards_Fair_Text_Classification__Expert_Ensemble_Debiasing_in_NLI.pdf'
excerpt: 'Bias in NLP models can occur from a variety of sources, making it critical to handle this issue comprehensively. In this paper we provide a thorough framework for increasing the fairness and reliability NLP models by using two methods (adversarial challenge sets and ensemble-based debiasing) as key techniques to effectively control the biases. We train the SNLI dataset on the electra-small-discriminator model as our main model and show its performance through assessment and analysis. The use of adversarial challenge sets is motivated to train the model on data that is intentionally created to fool the NLP model. Ensemble-based debiasing incorporates the collective intelligence of several expert models to provide predictions that are less prone to bias and error. Our experiment is divided into steps as follows: expert model(s) selection, training the main model, merging predictions using soft debiased labels, training with debiased labels, and final evaluation.'
---

