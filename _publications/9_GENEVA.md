---
title: "GENEVA: Benchmarking Generalizability for Event Argument Extraction with Hundreds of Event Types and Argument Roles"
collection: publications
Authors: 'Tanmay Parekh, <b>I-Hung Hsu</b>, Kuan-Hao Huang, Kai-Wei Chang, Nanyun Peng.'
date: 07/2023
venue: 'ACL'
paperurl: 'https://aclanthology.org/2023.acl-long.203/'
# presentationurl: 
codeurl: 'https://github.com/PlusLabNLP/GENEVA'
excerpt: ''
---
---
<a href='https://aclanthology.org/2023.acl-long.203/' target="_blank">[Download Paper]</a><a href='https://github.com/PlusLabNLP/GENEVA' target="_blank">[Source Code]</a>

<p align="justify">
Recent works in Event Argument Extraction (EAE) have focused on improving model generalizability to cater to new events and domains. However, standard benchmarking datasets like ACE and ERE cover less than 40 event types and 25 entity-centric argument roles. Limited diversity and coverage hinder these datasets from adequately evaluating the generalizability of EAE models. In this paper, we first contribute by creating a large and diverse EAE ontology. This ontology is created by transforming FrameNet, a comprehensive semantic role labeling (SRL) dataset for EAE, by exploiting the similarity between these two tasks. Then, exhaustive human expert annotations are collected to build the ontology, concluding with 115 events and 220 argument roles, with a significant portion of roles not being entities. We utilize this ontology to further introduce GENEVA, a diverse generalizability benchmarking dataset comprising four test suites aimed at evaluating models’ ability to handle limited data and unseen event type generalization. We benchmark six EAE models from various families. The results show that owing to non-entity argument roles, even the best-performing model can only achieve 39% F1 score, indicating how GENEVA provides new challenges for generalization in EAE. Overall, our large and diverse EAE ontology can aid in creating more comprehensive future resources, while GENEVA is a challenging benchmarking dataset encouraging further research for improving generalizability in EAE. The code and data can be found at https://github.com/PlusLabNLP/GENEVA.
</p>