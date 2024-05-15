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
excerpt: 'A common issue that arises when training NLP models is the inherent biases that exist in the training dataset. Bias in NLP models can occur from a variety of sources, making it critical to handle this issue comprehensively. In this paper we provide a thorough framework for increasing the fairness and reliability NLP models by using two methods (adversarial challenge sets and ensemble-based debiasing) as key techniques to effectively control the biases. We train the SNLI dataset on the electra-small-discriminator model as our main model and show its performance through assessment and analysis. The use of adversarial challenge sets is motivated to train the model on data that is intentionally created to fool the NLP model. Ensemble-based debiasing incorporates the collective intelligence of several expert models to provide predictions that are less prone to bias and error. Our experiment is divided into steps as follows: expert model(s) selection, training the main model, merging predictions using soft debiased labels, training with debiased labels, and final evaluation.'
---

Abhishek Divekar, Alex Stoken

**Description:**
A common issue when asking questions is that they might be prone to misinterpretation: most of us have experienced when a colleague or teacher misinterprets a question and provides an answer which is tangential to the information we desire, or incomplete. This problem is exacerbated over text, where visual and emotion cues are not transmittable. We hypothesize that question answering models face the same issues as the human responder in such situations: when asked an ambiguous question, they might be unsure what to retrieve from the given passage. We propose paraphrasing the question with pre-trained language models, to improve answer retrieval and robustness to ambiguous questions. We introduce a new scoring metric, GROK, to evaluate and select good paraphrases. We show that this metric improved upon paraphrase selection via beam search for downstream tasks, and that this metric combined with data augmentation via backtranslation increases question answering performance on the NewsQA and BioASQ datasets, improving EM by 2.5% and F1 by 1.9% over-and-above the baseline on the latter.

**My contribution:**
Formulated research question and GROK metric, wrote code to generate abstractive summaries and ran experiments to train hundreds of BiLSTM models on AWS GPUs.

**Resources:** [[Technical report](https://adivekar-utexas.github.io/files/UTCS-NLP-Question-Paraphrasing-Using-Cross-Domain-Abstractive-Summarization-and-Backtranslation.pdf)]
