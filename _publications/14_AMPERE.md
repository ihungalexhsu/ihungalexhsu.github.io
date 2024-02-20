---
title: "AMPERE: AMR-Aware Prefix for Generation-Based Event Argument Extraction Model"
collection: publications
Authors: '<b>I-Hung Hsu</b><sup>*</sup>, Zhiyu Xie<sup>*</sup>, Kuan-Hao Huang, Prem Natarajan, Nanyun Peng.'
date: 07/2023
venue: 'ACL'
paperurl: 'https://aclanthology.org/2023.acl-long.615/'
presentationurl: 'https://github.com/PlusLabNLP/AMPERE/blob/main/slide_AMPERE_Virtual_Video.mp4'
# codeurl: ''
excerpt: ''
---
---
<a href='https://aclanthology.org/2023.acl-long.615/' target="_blank">[Download Paper]</a><a href='https://github.com/PlusLabNLP/AMPERE' target="_blank">[Source Code]</a><a href='https://github.com/PlusLabNLP/AMPERE/blob/main/slide_AMPERE_Virtual_Video.mp4' target="_blank">[Video]</a><a href='https://github.com/PlusLabNLP/AMPERE/blob/main/AMPERE_Poster.pdf' target="_blank">[Poster]</a>

<p align="justify">
Event argument extraction (EAE) identifies event arguments and their specific roles for a given event. Recent advancement in generation-based EAE models has shown great performance and generalizability over classification-based models. However, existing generation-based EAE models mostly focus on problem re-formulation and prompt design, without incorporating additional information that has been shown to be effective for classification-based models, such as the abstract meaning representation (AMR) of the input passages. Incorporating such information into generation-based models is challenging due to the heterogeneous nature of the natural language form prevalently used in generation-based models and the structured form of AMRs. In this work, we study strategies to incorporate AMR into generation-based EAE models. We propose AMPERE, which generates AMR-aware prefixes for every layer of the generation model. Thus, the prefix introduces AMR information to the generation-based EAE model and then improves the generation. We also introduce an adjusted copy mechanism to AMPERE to help overcome potential noises brought by the AMR graph. Comprehensive experiments and analyses on ACE2005 and ERE datasets show that AMPERE can get 4% - 10% absolute F1 score improvements with reduced training data and it is in general powerful across different training sizes.
</p>