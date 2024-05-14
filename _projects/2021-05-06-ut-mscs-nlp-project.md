---
title: "Asking the Right Questions: Question Paraphrasing Using Cross-Domain Abstractive Summarization and Backtranslation"
collection: projects
urlslug: "ut-mscs-nlp-project"
type: "Academic"
permalink: /projects/2021-05-06-ut-mscs-nlp-project
contributors: "Abhishek Divekar, Alex Stoken"
contribution: "Formulated research question and GROK metric, wrote code to generate abstractive summaries and ran experiments to train hundreds of BiLSTM models on AWS GPUs."
date: 2021-05-06
teaserurl: 'asking-the-right-questions-table.png'
reporturl: 'https://adivekar-utexas.github.io/files/UTCS-NLP-Question-Paraphrasing-Using-Cross-Domain-Abstractive-Summarization-and-Backtranslation.pdf'
excerpt: 'A common issue when asking questions is that they might be prone to misinterpretation: most of us have experienced when a colleague or teacher misinterprets a question and provides an answer which is tangential to the information we desire, or incomplete. This problem is exacerbated over text, where visual and emotion cues are not transmittable. We hypothesize that question answering models face the same issues as the human responder in such situations: when asked an ambiguous question, they might be unsure what to retrieve from the given passage. We propose paraphrasing the question with pre-trained language models, to improve answer retrieval and robustness to ambiguous questions. We introduce a new scoring metric, GROK, to evaluate and select good paraphrases. We show that this metric improved upon paraphrase selection via beam search for downstream tasks, and that this metric combined with data augmentation via backtranslation increases question answering performance on the NewsQA and BioASQ datasets, improving EM by 2.5% and F1 by 1.9% over-and-above the baseline on the latter.'
---

Abhishek Divekar, Alex Stoken

**Description:**
A common issue when asking questions is that they might be prone to misinterpretation: most of us have experienced when a colleague or teacher misinterprets a question and provides an answer which is tangential to the information we desire, or incomplete. This problem is exacerbated over text, where visual and emotion cues are not transmittable. We hypothesize that question answering models face the same issues as the human responder in such situations: when asked an ambiguous question, they might be unsure what to retrieve from the given passage. We propose paraphrasing the question with pre-trained language models, to improve answer retrieval and robustness to ambiguous questions. We introduce a new scoring metric, GROK, to evaluate and select good paraphrases. We show that this metric improved upon paraphrase selection via beam search for downstream tasks, and that this metric combined with data augmentation via backtranslation increases question answering performance on the NewsQA and BioASQ datasets, improving EM by 2.5% and F1 by 1.9% over-and-above the baseline on the latter.

**My contribution:**
Formulated research question and GROK metric, wrote code to generate abstractive summaries and ran experiments to train hundreds of BiLSTM models on AWS GPUs.

**Resources:** [[Technical report](https://adivekar-utexas.github.io/files/UTCS-NLP-Question-Paraphrasing-Using-Cross-Domain-Abstractive-Summarization-and-Backtranslation.pdf)]
