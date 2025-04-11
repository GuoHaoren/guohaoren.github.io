---
title: "SDSimPoint: Shallow–Deep Similarity Learning for Few-Shot Point Cloud Semantic Segmentation"
collection: publications
category: manuscripts
authors: "Jiahui Wang, Haiyue Zhu, Haoren Guo, Abdullah Al Mamun, Cheng Xiang, Clarence W de Silva, Tong Heng Lee"
permalink: /publications/2025-tnnls
excerpt: 'Three-dimensional point cloud semantic segmentation is a core task in computer vision. While few-shot methods address limited-data scenarios better than fully supervised approaches, they often struggle to capture class-specific features due to class-agnostic pretraining. To overcome this, we propose SDSimPoint, a shallow–deep similarity learning network that models both shallow (e.g., geometry, color) and deep (e.g., context, semantics) similarities between support and query samples. We further introduce BEAM (Beyond-Episode Attention Module), which expands attention beyond a single episode using memory units, enhancing similarity modeling. Additionally, our learnable distance metric adapts to complex data distributions. SDSimPoint consistently outperforms baselines across multiple datasets in few-shot point cloud segmentation.'
date: 2025-03-24
venue: 'INDIN'
paperurl: 'https://ieeexplore-ieee-org.libproxy1.nus.edu.sg/abstract/document/9976119'
---

Three-dimensional point cloud semantic segmentation is a fundamental task in computer vision. As the fully supervised approaches suffer from the generalization issue with limited data, few-shot point cloud segmentation models have been proposed to address the flexible adaptation. Nevertheless, due to the class-agnostic nature of the few-shot pretraining, its pretrained feature extractor is hard to capture the class-related intrinsic and abstract information. Therefore, we introduce the new concept of shallow and deep similarities and propose a shallow–deep similarity learning network (SDSimPoint) that aims to learn both shallow (superficial geometry, color, etc.) and deep similarities (intrinsic context and semantics, etc.) between the support and query samples, thereby boosting the performance. Moreover, we design a beyond-episode attention module (BEAM) to enlarge the region of the attention mechanism from a single episode to the entire dataset by utilizing the memory units, which enhances the extraction ability to better capture the shallow and deep similarities. Furthermore, our distance metric function is learnable in the proposed framework, which can better adapt to complex data distributions. Our proposed SDSimPoint consistently demonstrates substantial improvements compared to baseline approaches across various datasets in diverse few-shot point cloud semantic segmentation settings.
[Paper](https://ieeexplore.ieee.org/abstract/document/10937251)

Citation:
```
@article{wang2025sdsimpoint,
  title={SDSimPoint: Shallow--Deep Similarity Learning for Few-Shot Point Cloud Semantic Segmentation},
  author={Wang, Jiahui and Zhu, Haiyue and Guo, Haoren and Al Mamun, Abdullah and Xiang, Cheng and de Silva, Clarence W and Lee, Tong Heng},
  journal={IEEE Transactions on Neural Networks and Learning Systems},
  year={2025},
  publisher={IEEE}
}
```
