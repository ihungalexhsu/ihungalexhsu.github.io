---
title: "Code-Switched Text Synthesis in Unseen Language Pairs"
collection: publications
Authors: '<b>I-Hung Hsu</b>, Avik Ray, Shubham Garg, Nanyun Peng, Jing Huang.'
date: 07/2023
venue: 'ACL-Findings'
paperurl: 'https://aclanthology.org/2023.findings-acl.318/'
presentationurl: 'https://github.com/PlusLabNLP/GLOSS/blob/master/slide_Gloss_Virtual_Video.mp4'
# codeurl: ''
excerpt: ''
---
---
<a href='https://aclanthology.org/2023.findings-acl.318/' target="_blank">[Download Paper]</a><a href='https://github.com/PlusLabNLP/GLOSS/blob/master/slide_Gloss_Virtual_Video.mp4' target="_blank">[Video]</a><a href='https://github.com/PlusLabNLP/GLOSS/blob/master/slide_Gloss.pptx' target="_blank">[Slides]</a>

<p align="justify">
Existing efforts on text synthesis for code-switching mostly require training on code-switched texts in the target language pairs, limiting the deployment of the models to cases lacking code-switched data. In this work, we study the problem of synthesizing code-switched texts for language pairs absent from the training data. We introduce GLOSS, a model built on top of a pre-trained multilingual machine translation model (PMMTM) with an additional code-switching module. This module, either an adapter or extra prefixes, learns code-switching patterns from code-switched data during training, while the primary component of GLOSS, i.e., the PMMTM, is frozen. The design of only adjusting the code-switching module prevents our model from overfitting to the constrained training data for code-switching. Hence, GLOSS exhibits the ability to generalize and synthesize code-switched texts across a broader spectrum of language pairs. Additionally, we develop a self-training algorithm on target language pairs further to enhance the reliability of GLOSS. Automatic evaluations on four language pairs show that GLOSS achieves at least 55% relative BLEU and METEOR scores improvements compared to strong baselines. Human evaluations on two language pairs further validate the success of GLOSS.
</p>