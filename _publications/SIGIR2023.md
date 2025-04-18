---
title: "M2EU: Meta Learning for Cold-start Recommendation via Enhancing User Preference Estimation"
collection: publications
date: 2023-07-19
venue: 'Proceedings of the 46th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR)'
paperurl: 'http://XiaoZHOUCAM.github.io/files/SIGIR2023.pdf'
---

Zhenchao Wu, **Xiao Zhou\***.

The cold-start problem is commonly encountered in recommender systems when delivering recommendations to users or items with limited interaction information and can seriously harm the performance of the system. To cope with this issue, meta-learning-based approaches have come to the rescue in recent years by enabling models to learn user preferences globally in the pre-training stage followed by local fine-tuning for a target user with only a few interactions. However, we argue that the user representation learned in this way may be inadequate to capture user preference well since solely utilizing his/her own interactions may be far from enough in cold-start scenarios. To tackle this problem, we propose a novel meta-learning method named M2EU to enrich the representations of cold-start users by incorporating the information from other similar users who are identified based on the similarity of both inherent attributes and historical interactions. In addition, we design an attention mechanism according to the variances of ratings in the aggregation of similar user embeddings. To further enhance the capability of user preference modeling, we devise different neural layers to generate user or item embeddings at the rating level and utilize the weight-sharing strategy to guarantee adequate parameters learning of neural layers in our meta-learning approach. In meta-training with mini-batching, we adopt an incremental learn- ing scheme to learn a set of generalized parameters for all tasks. Experimental results on the public benchmark datasets demonstrate that M2EU outperforms state-of-the-art methods through extensive quantitative evaluations in various cold-start scenarios.
