---
title: "TAGPRIME: A Unified Framework for Relational Structure Extraction"
collection: publications
Authors: '<b>I-Hung Hsu</b><sup>*</sup>, Kuan-Hao Huang<sup>*</sup>, Shuning Zhang, Wenxin Cheng, Premkumar Natarajan, Kai-Wei Chang, Nanyun Peng.'
date: 06/2023
venue: 'ACL'
paperurl: 'https://aclanthology.org/2023.acl-long.723/'
presentationurl: ../files/acl2023tagprime_slides.pdf
codeurl: 'https://github.com/PlusLabNLP/TagPrime'
excerpt: ''
---
---
<a href='https://aclanthology.org/2023.acl-long.723' target="_blank">[Download Paper]</a><a href='https://github.com/PlusLabNLP/TagPrime' target="_blank">[Source Code]</a><a href='../../files/acl2023tagprime_poster.pdf' target="_blank">[Poster]</a><a href='../../files/acl2023tagprime_slides.pdf' target="_blank">[Slides]</a>

<p align="justify">
Many tasks in natural language processing require the extraction of relationship information for a given condition, such as event argument extraction, relation extraction, and task-oriented semantic parsing. Recent works usually propose sophisticated models for each task independently and pay less attention to the commonality of these tasks and to have a unified framework for all the tasks. In this work, we propose to take a unified view of all these tasks and introduce TAGPRIME to address relational structure extraction problems. TAGPRIME is a sequence tagging model that appends priming words about the information of the given condition (such as an event trigger) to the input text. With the self-attention mechanism in pre-trained language models, the priming words make the output contextualized representations contain more information about the given condition, and hence become more suitable for extracting specific relationships for the condition. Extensive experiments and analyses on three different tasks that cover ten datasets across five different languages demonstrate the generality and effectiveness of TAGPRIME.
</p>