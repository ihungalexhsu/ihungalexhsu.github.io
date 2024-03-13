---
title: "Contextual Label Projection for Cross-Lingual Structure Extraction"
collection: publications
Authors: 'Tanymay Parekh, <b>I-Hung Hsu</b>, Kuan-Hao Huang, Kai-Wei Chang, Nanyun Peng.'
date: 06/2024
venue: 'NAACL'
paperurl: 'https://arxiv.org/pdf/2309.08943.pdf'
# presentationurl: ''
# codeurl: ''
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2309.08943.pdf' target="_blank">[Download Paper]</a>

<p align="justify">
Translating training data into target languages has proven beneficial for cross-lingual transfer. However, for structure extraction tasks, translating data requires a label projection step, which translates input text and obtains translated labels in the translated text jointly. Previous research in label projection mostly compromises translation quality by either facilitating easy identification of translated labels from translated text or using word-level alignment between translation pairs to assemble translated phrase-level labels from the aligned words. In this paper, we introduce CLAP, which first translates text to the target language and performs contextual translation on the labels using the translated text as the context, ensuring better accuracy for the translated labels. We leverage instruction-tuned language models with multilingual capabilities as our contextual translator, imposing the constraint of the presence of translated labels in the translated text via instructions. We compare CLAP with other label projection techniques for creating pseudo-training data in target languages on event argument extraction, a representative structure extraction task. Results show that CLAP improves by 2-2.5 F1-score over other methods on the Chinese and Arabic ACE05 datasets.
</p>