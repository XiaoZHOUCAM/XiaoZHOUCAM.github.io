---
title: "CGAP: Urban Region Representation Learning with Coarsened Graph Attention Pooling"
collection: publications
date: 2024-05-03
venue: 'Proceedings of 33rd International Joint Conference on Artificial Intelligence (IJCAI)'
paperurl: 'http://XiaoZHOUCAM.github.io/files/IJCAI24_CGAP.pdf'
---

Zhuo Xu & **Xiao Zhou**\*.

The explosion of massive urban data recently has provided us with a valuable opportunity to gain deeper insights into urban regions and the daily lives of residents. Urban region representation learning emerges as a crucial realm for fulfilling this task. Among deep learning approaches, graph neural networks (GNNs) have shown promise, given that city elements can be naturally represented as nodes with various connections between them as edges. However, many existing GNN approaches encounter challenges such as oversmoothing and limitations in capturing information from nodes in other regions, resulting in the loss of crucial urban information and a decline in region representation performance. To address these challenges, we leverage urban graph structure infor- mation and introduce a hierarchical graph pooling process called Coarsened Graph Attention Pooling (CGAP). CGAP features local attention units to create coarsened intermediate graphs and global features. Additionally, by incorporating urban region graphs and global features into a global attention layer, we harness relational information to enhance representation effectiveness. Furthermore, CGAP integrates region attributes such as Points of Interest (POIs) and inter-regional contexts like human mobility, enabling the exploitation of multi-modal urban data for more comprehensive representation learning. Experiments on three downstream tasks related to the UN Sustainable Development Goals validate the effectiveness of region representations learned by our approach. Experimental results and analyses demonstrate that CGAP excels in various socioeconomic prediction tasks compared to competitive baselines.
