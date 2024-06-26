---
title: "AttenWalker: Unsupervised Long-Document Question Answering via Attention-based Graph Walking"
collection: publications
permalink: /publication/2023-05-03-attenwalker-unsupervised-long-document-question-answering-via-attention-based-graph-walking
excerpt: 'In this study, we propose a new task, named unsupervised long-document question answering (**ULQA**), aiming to generate high-quality long-document QA instances in an unsupervised manner. Besides, we propose **AttenWalker**, a novel unsupervised method to aggregate and generate answers with long-range dependency so as to construct long-document QA pairs.'
date: 2023-05-03
venue: 'ACL 2023 Findings'
paperurl: 'https://aclanthology.org/2023.findings-acl.862/' 
citation: 'Yuxiang Nie, Heyan Huang, Wei Wei, and Xian-Ling Mao. 2023. AttenWalker: Unsupervised Long-Document Question Answering via Attention-based Graph Walking. Findings of the Association for Computational Linguistics: ACL 2023. Toronto, Canada: Association for Computational Linguistics.'
---

## Abstract
Annotating long-document question answering (long-document QA) pairs is time-consuming and expensive. To alleviate the problem, it might be possible to generate long-document QA pairs via unsupervised question answering (UQA) methods. However, existing UQA tasks are based on short documents, and can hardly incorporate long-range information. To tackle the problem, we propose a new task, named unsupervised long-document question answering (ULQA), aiming to generate high-quality long-document QA instances in an unsupervised manner. Besides, we propose AttenWalker, a novel unsupervised method to aggregate and generate answers with long-range dependency so as to construct long-document QA pairs. Specifically, AttenWalker is composed of three modules, i.e., span collector, span linker and answer aggregator. Firstly, the span collector takes advantage of constituent parsing and reconstruction loss to select informative candidate spans for constructing answers. Secondly, by going through the attention graph of a pre-trained long-document model, potentially interrelated text spans (that might be far apart) could be linked together via an attention-walking algorithm. Thirdly, in the answer aggregator, linked spans are aggregated into the final answer via the mask-filling ability of a pre-trained model. Extensive experiments show that AttenWalker outperforms previous methods on Qasper and NarrativeQA. In addition, AttenWalker also shows strong performance in the few-shot learning setting.

[Download paper here](https://aclanthology.org/2023.findings-acl.862.pdf)

Recommended citation: Yuxiang Nie, Heyan Huang, Wei Wei, and Xian-Ling Mao. 2023. AttenWalker: Unsupervised Long-Document Question Answering via Attention-based Graph Walking. Findings of the Association for Computational Linguistics: ACL 2023. Toronto, Canada: Association for Computational Linguistics.
