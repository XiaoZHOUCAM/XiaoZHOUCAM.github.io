---
title: "LaPR: Latent Preference Reasoning for Generative Personalized Retrieval"
collection: publications
date: 2026-10-24
venue: 'Proceedings of the 2026 Conference on Empirical Methods in Natural Language Processing (EMNLP)'
paperurl: 'http://XiaoZHOUCAM.github.io/files/EMNLP26_LaPR.pdf'
---

Hanze Guo<sup>&spades;</sup>, Shunyu Zhang<sup>&spades;</sup>, Jiakai Tang, Yi Zhang\*, Xuanping Li, Jingwei Zhuo, **Xiao Zhou**\*.

Generative retrieval offers a unified paradigm for personalized search by autoregressively decoding items as Semantic IDs. However, personalized search hinges on reasoning about query-history relevance, in which explicit textual reasoning incurs heavy cost and high latency, whereas purely implicit reasoning does not provide a structured intermediate latent interface for retrieval. To resolve this tension, we propose LaPR, an adaptive latent retrieval reasoning framework that turns explicit retrieval reasoning into compact latent signals. Specifically, LaPR constructs verified step-wise retrieval traces, induces step-conditioned semantic slots via vector quantization, and distills textual reasoning into these slots through a text-latent to pure-latent curriculum. At inference, LaPR adaptively predicts the reasoning depth and corresponding slots from the query and user history, providing latent reasoning signals for efficient Semantic-ID generation. Extensive experiments show that LaPR consistently surpasses all baselines, achieving SOTA personal retrieval performance while substantially reducing reasoning-token cost and inference latency.
