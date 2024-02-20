---
title: "Summarization as Indirect Supervision for Relation Extraction"
collection: publications
Authors: 'Keming Lu, <b>I-Hung Hsu</b>, Wenxuan Zhou, Mingyu Derek Ma, Muhao Chen.'
date: 11/2022
venue: 'EMNLP-Findings'
paperurl: 'https://aclanthology.org/2022.findings-emnlp.490/'
# presentationurl: 
codeurl: 'https://github.com/luka-group/SuRE'
excerpt: ''
---
---
<a href='https://aclanthology.org/2022.findings-emnlp.490/' target="_blank">[Download Paper]</a><a href='https://github.com/luka-group/SuRE' target="_blank">[Source Code]</a>

<p align="justify">
Relation extraction (RE) models have been challenged by their reliance on training data with expensive annotations. Considering that summarization tasks aim at acquiring concise expressions of synoptical information from the longer context, these tasks naturally align with the objective of RE, i.e., extracting a kind of synoptical information that describes the relation of entity mentions. We present SuRE, which converts RE into a summarization formulation. SuRE leads to more precise and resource-efficient RE based on indirect supervision from summarization tasks. To achieve this goal, we develop sentence and relation conversion techniques that essentially bridge the formulation of summarization and RE tasks. We also incorporate constraint decoding techniques with Trie scoring to further enhance summarization-based RE with robust inference. Experiments on three RE datasets demonstrate the effectiveness of SuRE in both full-dataset and low-resource settings, showing that summarization is a promising source of indirect supervision signals to improve RE models.
</p>