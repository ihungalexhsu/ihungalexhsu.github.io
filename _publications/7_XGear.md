---
title: "Multilingual Generative Language Models for Zero-Shot Cross-Lingual Event Argument Extraction"
collection: publications
Authors: 'Kuan-Hao Huang<sup>*</sup>, <b>I-Hung Hsu</b><sup>*</sup>, Prem Natarajan, Kai-Wei Chang, Nanyun Peng.'
date: 05/2022
venue: 'ACL'
paperurl: 'https://aclanthology.org/2022.acl-long.317/'
presentationurl: ../files/acl2022xgear_slides.pdf
codeurl: 'https://github.com/pluslabnlp/x-gear'
excerpt: ''
---
---
<a href='https://aclanthology.org/2022.acl-long.317/' target="_blank">[Download Paper]</a><a href='https://github.com/pluslabnlp/x-gear' target="_blank">[Source Code]</a><a href='../files/acl2022xgear_poster.pdf' target="_blank">[Poster]</a><a href='../files/acl2022xgear_slides.pdf' target="_blank">[Slides]</a>

<p align="justify">
We present a study on leveraging multilingual pre-trained generative language models for zero-shot cross-lingual event argument extraction (EAE). By formulating EAE as a language generation task, our method effectively encodes event structures and captures the dependencies between arguments. We design language-agnostic templates to represent the event argument structures, which are compatible with any language, hence facilitating the cross-lingual transfer. Our proposed model finetunes multilingual pre-trained generative language models to generate sentences that fill in the language-agnostic template with arguments extracted from the input passage. The model is trained on source languages and is then directly applied to target languages for event argument extraction. Experiments demonstrate that the proposed model outperforms the current state-of-the-art models on zero-shot cross-lingual EAE. Comprehensive studies and error analyses are presented to better understand the advantages and the current limitations of using generative language models for zero-shot cross-lingual transfer EAE.
</p>