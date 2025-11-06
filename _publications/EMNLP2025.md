---
title: "AutoMIR: Effective Zero-Shot Medical Information Retrieval without Relevance Labels"
collection: publications
date: 2025-11-04
venue: 'Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing (EMNLP)'
paperurl: 'http://XiaoZHOUCAM.github.io/files/EMNLP25_AutoMIR.pdf'
---

Lei Li, Xiangxu Zhang, **Xiao Zhou**\*, Zheng Liu*.

Medical information retrieval (MIR) is vital for accessing knowledge from electronic health records, scientific literature, and medical databases, supporting applications such as medical education, patient queries, and clinical diagnosis. However, effective zero-shot dense retrieval in the medical domain remains difficult due to the scarcity of relevance-labeled data. To address this challenge, we propose Self-Learning Hypothetical Document Embeddings (SL-HyDE), a framework that leverages large language models (LLMs) to generate hypothetical documents conditioned on a query. These documents encapsulate essential medical context, guiding dense retrievers toward the most relevant results. SL-HyDE further employs a self-learning mechanism that iteratively improves pseudo-document generation and retrieval using unlabeled corpora, eliminating the need for labeled data. In addition, we introduce the Chinese Medical Information Retrieval Benchmark (CMIRB), a comprehensive evaluation suite reflecting real-world medical scenarios, comprising five tasks and ten datasets. By benchmarking ten models on CMIRB, we provide a rigorous standard for evaluating MIR systems. Experimental results demonstrate that SL-HyDE significantly outperforms HyDE in retrieval accuracy, while exhibiting strong generalization and scalability across diverse LLM and retriever configurations. Our code and data are publicly available at: https://github.com/ll0ruc/AutoMIR.
