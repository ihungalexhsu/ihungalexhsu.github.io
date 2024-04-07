---
title: "Contextual Label Projection for Cross-Lingual Structure Extraction"
collection: publications
Authors: 'Tanymay Parekh, <b>I-Hung Hsu</b>, Kuan-Hao Huang, Kai-Wei Chang, Nanyun Peng.'
date: 06/2024
venue: 'NAACL'
paperurl: 'https://arxiv.org/pdf/2309.08943.pdf'
# presentationurl: ''
codeurl: 'https://github.com/PlusLabNLP/CLaP'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2309.08943.pdf' target="_blank">[Download Paper]</a><a href='https://github.com/PlusLabNLP/CLaP' target="_blank">[Source Code]</a>

<p align="justify">
Label projection, which involves obtaining translated labels and texts jointly, is essential for leveraging machine translation to facilitate cross-lingual transfer in structured prediction tasks. Prior research exploring label projection often compromise translation accuracy by favoring simplified label translation or relying solely on word-level alignments. In this paper, we introduce a novel label projection approach, CLaP, which translates text to the target language and performs contextual translation on the labels using the translated text as the context, ensuring better accuracy for the translated labels. We leverage instruction-tuned language models with multilingual capabilities as our contextual translator, imposing the constraint of the presence of translated labels in the translated text via instructions. We benchmark CLaP with other label projection techniques on zero-shot cross-lingual transfer across 39 languages on two representative structured prediction tasks - event argument extraction (EAE) and named entity recognition (NER), showing over 2.4 F1 improvement for EAE and 1.4 F1 improvement for NER. We further explore the applicability of CLaP on ten extremely low-resource languages to showcase its potential for cross-lingual structured prediction.
</p>