---
title: "Mix-Initiative Response Generation with Dynamic Prefix Tuning"
collection: publications
permalink: /publication/2024-06-17-mix-Initiative-response-generation-with-dynamic-prefix-tuning
excerpt: 'In this work, we propose a general mix-Initiative Dynamic Prefix Tuning framework (IDPT) to decouple different initiatives from the generation model.'
date: 2024-06-17
venue: 'NAACL 2024'
paperurl: 'https://aclanthology.org/2024.naacl-long.485/'
citation: 'Yuxiang Nie, Heyan Huang, Xian-Ling Mao, and Lizi Liao. 2024. Mix-Initiative Response Generation with Dynamic Prefix Tuning. In Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Mexico City, Mexico. Association for Computational Linguistics.'
---

## Abstract
Mixed initiative serves as one of the key factors in controlling conversation directions. For a speaker, responding passively or leading proactively would result in rather different responses. However, most dialogue systems focus on training a holistic response generation model without any distinction among different initiatives. It leads to the cross-contamination problem, where the model confuses different initiatives and generates inappropriate responses. Moreover, obtaining plenty of human annotations for initiative labels can be expensive. To address this issue, we propose a general mix-Initiative Dynamic Prefix Tuning framework (IDPT) to decouple different initiatives from the generation model, which learns initiative-aware prefixes in both supervised and unsupervised settings. Specifically, IDPT decouples initiative factors into different prefix parameters and uses the attention mechanism to adjust the selection of initiatives in guiding generation dynamically. The prefix parameters can be tuned towards accurate initiative prediction as well as mix-initiative response generation. Extensive experiments on two public dialogue datasets show that the proposed IDPT outperforms previous baselines on both automatic metrics and human evaluations. It also manages to generate appropriate responses with manipulated initiatives.

[Download paper here](https://aclanthology.org/2024.naacl-long.485.pdf)

Recommended citation: Yuxiang Nie, Heyan Huang, Xian-Ling Mao, and Lizi Liao. 2024. Mix-Initiative Response Generation with Dynamic Prefix Tuning. In Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Mexico City, Mexico. Association for Computational Linguistics.
