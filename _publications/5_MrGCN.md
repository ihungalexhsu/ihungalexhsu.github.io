---
title: "Discourse-level Relation Extraction via Graph Pooling"
collection: publications
Authors: 'I-Hung Hsu, Xiao Guo, Premkumar Natarajan, Nanyun Peng.'
date: 02/2022
venue: 'DLG-AAAI Workshop'
paperurl: 'https://aclanthology.org/2021.emnlp-main.597/'
# presentationurl: ''
# codeurl: ''
excerpt: ''
---
---
<a href='https://arxiv.org/abs/2101.00124' target="_blank">[Download Paper]</a>

<p align="justify">
The ability to capture complex linguistic structures and long-term dependencies among words in the passage is essential for discourse-level relation extraction (DRE) tasks. Graph neural networks (GNNs), one of the methods to encode dependency graphs, have been shown effective in prior works for DRE. However, relatively little attention has been paid to receptive fields of GNNs, which can be crucial for cases with extremely long text that requires discourse understanding. In this work, we leverage the idea of graph pooling and propose to use pooling-unpooling framework on DRE tasks. The pooling branch reduces the graph size and enables the GNNs to obtain larger receptive fields within fewer layers; the unpooling branch restores the pooled graph to its original resolution so that representations for entity mention can be extracted. We propose Clause Matching (CM), a novel linguistically inspired graph pooling method for NLP tasks. Experiments on two DRE datasets demonstrate that our models significantly improve over baselines when modeling long-term dependencies is required, which shows the effectiveness of the pooling-unpooling framework and our CM pooling method.
</p>