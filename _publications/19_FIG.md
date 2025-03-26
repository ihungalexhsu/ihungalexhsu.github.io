---
title: "FIG: Forward-Inverse Generation for Low-Resource Domain-specific Event Detection"
collection: preprint
Authors: 'Tanmay Parekh, Yuxuan Dong, Lucas Bandarkar, Artin Kim, <b>I-Hung Hsu</b>, Kai-Wei Chang, Nanyun Peng.'
date: 02/2025
venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/2502.17394'
# presentationurl: ''
# codeurl: ''
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2502.17394' target="_blank">[Download Paper]</a>

<p align="justify">
Event Detection (ED) is the task of identifying typed event mentions of interest from natural language text, which benefits domain-specific reasoning in biomedical, legal, and epidemiological domains. However, procuring supervised data for thousands of events for various domains is a laborious and expensive task. To this end, existing works have explored synthetic data generation via forward (generating labels for unlabeled sentences) and inverse (generating sentences from generated labels) generations. However, forward generation often produces noisy labels, while inverse generation struggles with domain drift and incomplete event annotations. To address these challenges, we introduce FIG, a hybrid approach that leverages inverse generation for high-quality data synthesis while anchoring it to domain-specific cues extracted via forward generation on unlabeled target data. FIG further enhances its synthetic data by adding missing annotations through forward generation-based refinement. Experimentation on three ED datasets from diverse domains reveals that FIG outperforms the best baseline achieving average gains of 3.3% F1 and 5.4% F1 in the zero-shot and few-shot settings respectively. Analyzing the generated trigger hit rate and human evaluation substantiates FIG's superior domain alignment and data quality compared to existing baselines.
</p>
