---
title: "Remaining Useful Life Prediction via Frequency Emphasizing Mix-Up and Masked Reconstruction"
collection: publications
category: manuscripts
authors: 'Haoren Guo, Haiyue Zhu, Jiahui Wang, Vadakkepat Prahlad, Weng Khuen Ho, Clarence W de Silva, Tong Heng Lee'
permalink: /publications/2023-TAI
excerpt: 'This paper addresses the challenge of predicting Remaining Useful Lifetime (RUL) in machinery within Industry 4.0 by proposing a framework that improves data utilization through frequency-domain analysis and semi-supervised learning. The Frequency Emphasizing Mix-Up Module (FEMM) enhances feature extraction, while the Masked Autoencoder Reconstruction Auxiliary Learning (MARAL) utilizes unlabeled data from unrestricted domains. Evaluations on the C-MAPSS dataset show the model outperforms others, achieving significant accuracy improvements, particularly with minimal labeled data. The results demonstrate a notable reduction in RMSE and overall prediction error.'
date: 2024-05-03
venue: 'IEEE Transaction on Artificial Intelligence (TAI)'
paperurl: 'https://ieeexplore-ieee-org.libproxy1.nus.edu.sg/abstract/document/10518144'
---
Impact Statement:
In Industry 4.0, accurately predicting the RUL of machinery is pivotal for modern manufacturing efficiency. However, unlike other tasks where labels can be easily obtained through manpower, RUL labels can only be acquired after machines break down, making the process more costly. Our proposed FEMM can effectively improve data utilization efficiency by leveraging the intrinsically decomposed frequency-domain information. Furthermore, our novel-designed MARAL allows our model to leverage unrestricted domain data, substantially boosting its efficacy, particularly when labeled data availability is limited. Evaluations on the C-MAPSS dataset highlight our method’s superiority, particularly in FD004, with a 10.75% drop in RMSE and a 39.69% score reduction compared to the second-best results. Impressively, by introducing unrestricted domain data for auxiliary learning, with just 10% labeled data, here is a 98.09% score drop and 70.28% RMSE decline compared to the fully supervised model.

Abstract:
The prediction of the remaining useful lifetime (RUL) of machines and tools is crucial in the realm of modern manufacturing and in the framework of Industry 4.0. Recent deep learning techniques offer an opportunity for the utilization of data-driven methods in RUL prediction. However, the persistent data scarcity issue presents a thorny bottleneck in the machinery RUL prediction tasks due to the high cost of labeled training data collection. In this article, we propose an effective learning framework for RUL prediction consisting of two novel methodological modules to improve data utilization efficiency. The first module is to leverage the intrinsically decomposed frequency-domain information to boost the effective feature extraction with a novel-designed frequency emphasizing mix-up module (FEMM) . The second one involves incorporating semisupervised learning to make use of unrestricted domain unlabeled data to overcome the constraints associated with data scarcity where we introduced masked autoencoder reconstruction auxiliary learning (MARAL) to the model. In addition, to better obtain temporal information, an LSTM temporal projection layer is designed. The proposed method was evaluated through experiments conducted on the commercial modular aero-propulsion system simulation (C-MAPSS) datasets, and our results show that the proposed method outperforms existing other methods in terms of both accuracy and effectiveness in the RUL prediction. In addition, our experimental results demonstrate that the proposed method is able to leverage unrestricted domain datasets to significantly boost model performance under low-data scenarios.
[paper](https://ieeexplore-ieee-org.libproxy1.nus.edu.sg/abstract/document/10518144)

Citation
```
@article{guo2024remaining,
  title={Remaining Useful Life Prediction via Frequency Emphasizing Mix-Up and Masked Reconstruction},
  author={Guo, Haoren and Zhu, Haiyue and Wang, Jiahui and Prahlad, Vadakkepat and Ho, Weng Khuen and de Silva, Clarence W and Lee, Tong Heng},
  journal={IEEE Transactions on Artificial Intelligence},
  year={2024},
  publisher={IEEE}
}
```
