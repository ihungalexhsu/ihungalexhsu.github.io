---
title: "Deep structured neural network for event temporal relation extraction"
collection: publications
Authors: 'Rujun Han<sup>*</sup>, <b>I-Hung Hsu</b><sup>*</sup>, Mu Yang, Aram Galstyan, Ralph Weischedel, Nanyun Peng.'
date: 11/2019
venue: 'CoNLL'
paperurl: 'https://aclanthology.org/K19-1062/'
# presentationurl: ''
codeurl: 'https://github.com/PlusLabNLP/Deep-Structured-EveEveTemp'
excerpt: ''
---
---
<a href='https://aclanthology.org/K19-1062/' target="_blank">[Download Paper]</a><a href='https://github.com/PlusLabNLP/Deep-Structured-EveEveTemp' target="_blank">[Source Code]</a>

<p align="justify">
We propose a novel deep structured learning framework for event temporal relation extraction. The model consists of 1) a recurrent neural network (RNN) to learn scoring functions for pair-wise relations, and 2) a structured support vector machine (SSVM) to make joint predictions. The neural network automatically learns representations that account for long-term contexts to provide robust features for the structured model, while the SSVM incorporates domain knowledge such as transitive closure of temporal relations as constraints to make better globally consistent decisions. By jointly training the two components, our model combines the benefits of both data-driven learning and knowledge exploitation. Experimental results on three high-quality event temporal relation datasets (TCR, MATRES, and TB-Dense) demonstrate that incorporated with pre-trained contextualized embeddings, the proposed model achieves significantly better performances than the state-of-the-art methods on all three datasets. We also provide thorough ablation studies to investigate our model.
</p>