---
title: "Controllable Affective Generation via Latent Vector Steering"
collection: publications
date: 2026-10-24
venue: 'Findings of the Association for Computational Linguistics: EMNLP 2026'
paperurl: 'http://XiaoZHOUCAM.github.io/files/EMNLP26_EmoVec.pdf'
---

Xixian Yong, Siyuan Chang, Yingying Zhang, Xian Wu\*, **Xiao Zhou**\*.

Large Language Models (LLMs) often produce emotionally flattened responses after alignment, limiting their effectiveness in affect-sensitive applications. In this paper, we propose EmoVec, a lightweight framework for controllable affective generation via latent vector
steering. EmoVec extracts emotion-specific directions from paired neutral and emotion-conditioned responses using contrastive activation addition, and further refines them through task-specific debiasing and principal subspace removal. During inference, these vectors are injected into the final residual stream with static or scenario-adaptive scaling, enabling continuous control over emotional intensity without updating model weights. Experiments across three LLMs and eight emotions show that EmoVec consistently improves emotional salience while largely preserving semantic content, fluency, and coherence. Ablation studies and human evaluation further confirm the effectiveness of vector purification and adaptive scaling, establishing EmoVec as a practical inference-time method for affective control in deployed LLMs. Code and data are available at https://github.com/chicosirius/EmoVec.
