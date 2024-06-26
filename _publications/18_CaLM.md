---
title: "CaLM: Contrasting Large and Small Language Models to Verify Grounded Generation"
collection: publications
Authors: '<b>I-Hung Hsu</b>, Zifeng Wang, Long T. Le, Lesly Miculicich, Nanyun Peng, Chen-Yu Lee, Tomas Pfister.'
date: 07/2024
venue: 'ACL-Findings'
paperurl: 'https://arxiv.org/abs/2406.05365.pdf'
# presentationurl: ''
# codeurl: ''
excerpt: ''
---
---
<a href='https://arxiv.org/abs/2406.05365.pdf' target="_blank">[Download Paper]</a>

<p align="justify">
Event linking connects event mentions in text with relevant nodes in a knowledge base (KB). Prior research in event Grounded generation aims to equip language models (LMs) with the ability to produce more credible and accountable responses by accurately citing verifiable sources. However, existing methods, by either feeding LMs with raw or preprocessed materials, remain prone to errors. To address this, we introduce CaLM, a novel verification framework. CaLM leverages the insight that a robust grounded response should be consistent with information derived solely from its cited sources. Our framework empowers smaller LMs, which rely less on parametric memory and excel at processing relevant information given a query, to validate the output of larger LMs. Larger LM responses that closely align with the smaller LMs' output, which relies exclusively on cited documents, are verified. Responses showing discrepancies are iteratively refined through a feedback loop. Experiments on three open-domain question-answering datasets demonstrate significant performance gains of 1.5% to 7% absolute average without any required model fine-tuning.
</p>