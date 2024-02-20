---
title: "DEGREE: A Data-Efficient Generation-Based Event Extraction Model"
collection: publications
Authors: '<b>I-Hung Hsu</b><sup>*</sup>, Kuan-Hao Huang<sup>*</sup>, Elizabeth Boschee, Scott Miller, Premkumar Natarajan, Kai-Wei Chang, Nanyun Peng.'
date: 07/2022
venue: 'NAACL'
paperurl: 'https://aclanthology.org/2022.naacl-main.138/'
presentationurl: 'https://github.com/PlusLabNLP/DEGREE/blob/master/slide_degree_naacl2022.pdf'
codeurl: 'https://github.com/PlusLabNLP/DEGREE'
excerpt: ''
---
---
<a href='https://aclanthology.org/2022.naacl-main.138/' target="_blank">[Download Paper]</a><a href='https://github.com/PlusLabNLP/DEGREE' target="_blank">[Source Code]</a><a href='https://github.com/PlusLabNLP/DEGREE/blob/master/Pre-recorded_Video_NAACL2022_Degree.mp4' target="_blank">[Video]</a><a href='https://github.com/PlusLabNLP/DEGREE/blob/master/slide_degree_naacl2022.pdf' target="_blank">[Slides]</a>

<p align="justify">
Event extraction requires high-quality expert human annotations, which are usually expensive. Therefore, learning a data-efficient event extraction model that can be trained with only a few labeled examples has become a crucial challenge. In this paper, we focus on low-resource end-to-end event extraction and propose DEGREE, a data-efficient model that formulates event extraction as a conditional generation problem. Given a passage and a manually designed prompt, DEGREE learns to summarize the events mentioned in the passage into a natural sentence that follows a predefined pattern. The final event predictions are then extracted from the generated sentence with a deterministic algorithm. DEGREE has three advantages to learn well with less training data. First, our designed prompts provide semantic guidance for DEGREE to leverage DEGREE and thus better capture the event arguments. Moreover, DEGREE is capable of using additional weakly-supervised information, such as the description of events encoded in the prompts. Finally, DEGREE learns triggers and arguments jointly in an end-to-end manner, which encourages the model to better utilize the shared knowledge and dependencies among them. Our experimental results demonstrate the strong performance of DEGREE for low-resource event extraction.
</p>