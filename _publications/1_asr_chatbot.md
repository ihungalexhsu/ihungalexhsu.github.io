---
title: "Mitigating the Impact of Speech Recognition Errors on Chatbot using Sequence-to-Sequence Model"
collection: publications
Authors: 'Pin-Jung Chen<sup>*</sup>, <b>I-Hung Hsu</b><sup>*</sup>, Yi-Yao Huang<sup>*</sup>, Hung-Yi Lee.'
date: 12/2017
venue: 'IEEE ASRU'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/8268977'
presentationurl: ''
codeurl: 'https://github.com/ihungalexhsu/Domain_Adaptation_on_ASR_dialogue_system'
excerpt: ''
---
---
<a href='https://arxiv.org/abs/1709.07862' target="_blank">[Download Paper]</a><a href='https://github.com/ihungalexhsu/Domain_Adaptation_on_ASR_dialogue_system' target="_blank">[Source Code]</a>

<p align="justify">
We apply sequence-to-sequence model to mitigate the impact of speech recognition errors on open domain end-to-end dialog generation. We cast the task as a domain adaptation problem where ASR transcriptions and original text are in two different domains. In this paper, our proposed model includes two individual encoders for each domain data and make their hidden states similar to ensure the decoder predict the same dialog text. The method shows that the sequence-to-sequence model can learn the ASR transcriptions and original text pair having the same meaning and eliminate the speech recognition errors. Experimental results on Cornell movie dialog dataset demonstrate that the domain adaption system help the spoken dialog system generate more similar responses with the original text answers.
</p>