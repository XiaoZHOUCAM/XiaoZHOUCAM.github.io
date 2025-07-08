---
title: "MuseCL: Predicting Urban Socioeconomic Indicators via Multi-Semantic Contrastive Learning"
collection: publications
date: 2024-05-03
venue: 'Proceedings of 33rd International Joint Conference on Artificial Intelligence (IJCAI)'
paperurl: 'http://XiaoZHOUCAM.github.io/files/IJCAI24_MuseCL.pdf'
---

Xixian Yong & **Xiao Zhou**\*.

Predicting socioeconomic indicators within urban regions is crucial for fostering inclusivity, resilience, and sustainability in cities and human settlements. While pioneering studies have attempted to leverage multi-modal data for socioe-conomic prediction, jointly exploring their underlying semantics remains a significant challenge. To address the gap, this paper introduces a Multi-Semantic Contrastive Learning (MuseCL) framework for fine-grained urban region profiling and socioeconomic prediction. Within this framework, we initiate the process by constructing contrastive sample pairs for street view and remote sensing images, capitalizing on the similarities in human mobility and Point of Interest (POI) distribution to derive semantic features from the visual modality. Additionally, we extract semantic insights from POI texts embedded within these regions, employing a pre-trained text encoder. To merge the acquired visual and textual features, we devise an innovative cross-modality-based attentional fusion module, which leverages a contrastive mechanism for integration. Experimental results across multi- ple cities and indicators consistently highlight the superiority of MuseCL, demonstrating an average improvement of 10% in R2 compared to various competitive baseline models. The code of this work is publicly available at https://github.com/XixianYong/MuseCL.
