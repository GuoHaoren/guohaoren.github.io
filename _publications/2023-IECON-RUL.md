---
title: "Lightweight Compressed Temporal and Compressed Spatial Attention with Augmentation Fusion in Remaining Useful Life Prediction"
collection: publications
category: conferences
authors: 'Haoren Guo, Haiyue Zhu, Jiahui Wang, Vadakkepat Prahlad, Weng Khuen Ho, Clarence W de Silva, Tong Heng Lee'
permalink: /publication/2023-iecon-rul
excerpt: 'This paper proposes a non-transformer model, Compressed Temporal and Compressed Spatial (CTCS) Attention, for predicting Remaining Useful Lifetime (RUL), addressing concerns with transformer-based models such as high computational complexity and ineffective handling of low data. The CTCS model efficiently captures temporal and spatial information with pre- and post-positional encodings, while an Augmentation Fusion Module (AFM) improves understanding of data invariances. Evaluated on the C-MAPSS dataset, the proposed model outperforms transformer-based methods in accuracy while reducing computational cost by up to 32 times fewer FLOPs.'
date: 2023-10-16
venue: 'IECON'
paperurl: 'https://ieeexplore-ieee-org.libproxy1.nus.edu.sg/abstract/document/10312336'
---

Data-driven models for predicting the Remaining Useful Lifetime (RUL) have gained popularity due to their efficiency to enhance industrial security and reduce economic losses. Recently, there has been a notable rise in the research of transformer-based models for RUL prediction. While transformer-based models have shown significant improvements over previous LSTM-based and CNN-based models, we have raised concerns regarding high computational complexity, in-effective training with low data, no sensitivity to the order of the time series, and permutation invariant on its application to RUL prediction. The persistent issue of data scarcity and the importance of capturing the temporal relations in RUL prediction further question the suitability of transformer-based models. Considering these, We propose a simple non-transformer model, Compressed Temporal and Compressed Spatial (CTCS) Attention, which is efficient and lightweight, to capture both temporal and spatial information with the incorporation of pre- and post-positional encodings. Additionally, we introduce an Augmentation Fusion Module (AFM) to enhance the comprehension ability of the invariant characteristics of the data. The proposed methodology is evaluated on the NASA Commercial Modular Aero-Propulsion System Simulation (C-MAPSS) dataset and comprehensive experiments show that our proposed method not only surpasses other methods but outperforms the transformer-based model while requiring significantly fewer Floating-point operations (FLOPs), up to 32 times less.
[paper](https://ieeexplore-ieee-org.libproxy1.nus.edu.sg/abstract/document/10312336)

Citation
```
@inproceedings{guo2023lightweight,
  title={Lightweight Compressed Temporal and Compressed Spatial Attention with Augmentation Fusion in Remaining Useful Life Prediction},
  author={Guo, Haoren and Zhu, Haiyue and Wang, Jiahui and Prahlad, Vadakkepat and Ho, Weng Khuen and de Silva, Clarence W and Lee, Tong Heng},
  booktitle={IECON 2023-49th Annual Conference of the IEEE Industrial Electronics Society},
  pages={1--6},
  year={2023},
  organization={IEEE}
}

```
