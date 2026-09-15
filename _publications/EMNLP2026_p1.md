---
title: "R2MED: A Benchmark for Reasoning-Driven Medical Retrieval"
collection: publications
date: 2026-07-02
venue: 'Proceedings of the 2026 Conference on Empirical Methods in Natural Language Processing (EMNLP)'
paperurl: 'http://XiaoZHOUCAM.github.io/files/EMNLP26_R2MED.pdf'
---

Xiangxu Zhang<sup>&spades;</sup>, Lei Li<sup>&spades;</sup>, Zheng Liu\*, **Xiao Zhou**\*.

Current medical retrieval benchmarks primarily emphasize lexical or shallow semantic similarity, overlooking the reasoning-intensive demands that are central to clinical decision-making. In practice, physicians often retrieve authoritative medical evidence to support diagnostic hypotheses. Such evidence typically aligns with an inferred diagnosis rather than the surface form of a patient’s symptoms, leading to low lexical or semantic overlap between queries and relevant documents. To address this gap, we introduce R2MED, the first benchmark explicitly designed for reasoning-driven medical retrieval. It comprises 876 queries spanning three tasks: Q&A reference retrieval, clinical evidence retrieval, and clinical case retrieval. These tasks are drawn from five representative medical scenarios and twelve body systems, capturing the complexity and diversity of real-world medical information needs. We evaluate 15 widely-used retrieval systems on R2MED and find that even the best model achieves only 31.4 nDCG@10, demonstrating the benchmark’s difficulty. Classical re-ranking and generation-augmented retrieval methods offer only modest improvements. Although large reasoning models improve performance via intermediate inference generation, the best results still peak at 41.4 nDCG@10. These findings underscore a substantial gap between current retrieval techniques and the reasoning demands of real clinical tasks. We release R2MED as a challenging benchmark to foster the development of next-generation medical retrieval systems with enhanced reasoning capabilities.
