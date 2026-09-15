---
title: "From Static Personal Values to Contextualized Personalization: Bayesian Personalized Value Alignment for LLMs"
collection: publications
date: 2026-10-24
venue: 'Findings of the Association for Computational Linguistics: EMNLP 2026'
paperurl: 'http://XiaoZHOUCAM.github.io/files/EMNLP26_BaCVA.pdf'
---

Hanze Guo<sup>&spades;</sup>, Aixuan Song<sup>&spades;</sup>, Jing Yao<sup>&spades;</sup>, Xiangxu Zhang, Xiaoyuan Yi, Xing Xie, **Xiao Zhou**\*.

Personalized value alignment has become increasingly important as large language models (LLMs) are expected to accommodate diverse user preferences. However, existing methods typically align model outputs with a static value profile across prompts, overlooking that the salience of value dimensions varies substantially across contexts. Inspired by Lewin’s Field Theory, which views human behavior as jointly shaped by personal dispositions and situational constraints, we model personal values as priors and context-dependent preferences as posteriors. We propose BaCVA, an
inference-time Bayesian Context-aware personalized Value Alignment method that approximates posterior personalized preferences by integrating static personal values with scenario-specific value salience. BaCVA first estimates contextual value salience from generally normative responses, and then employs a dual-view personalization module to infer posterior preferences from complementary personal-value and scenario-driven perspectives. This Bayesian formulation enables more accurate and adaptive personalized value alignment while improving data efficiency via prior values. Extensive experiments on benchmarks demonstrate its superiority over strong baselines.
