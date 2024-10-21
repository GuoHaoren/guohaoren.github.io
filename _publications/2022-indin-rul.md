---
title: "Masked Self-Supervision for Remaining Useful Lifetime Prediction in Machine Tools"
collection: publications
category: conferences
permalink: /publications/2022-indin-rul
authors: 'Haoren Guo, Haiyue Zhu, Jiahui Wang, Prahlad Vadakkepat, Weng Khuen Ho, Tong Heng Lee'
excerpt: '
Predicting the Remaining Useful Lifetime (RUL) of machines is crucial for preventing tool wear and breakdown in Industry 4.0, but fully-supervised models struggle due to limited labeled data from broken machines. To address this, the authors propose a masked self-supervised learning method that uses unlabeled data for RUL prediction, showing superior performance on the C-MAPSS dataset compared to fully-supervised approaches.'
date: 2022-07-25
venue: 'INDIN'
paperurl: 'https://ieeexplore-ieee-org.libproxy1.nus.edu.sg/abstract/document/9976158'
---

Prediction of Remaining Useful Lifetime (RUL) in the modern manufacturing and automation workplace for machines and tools is essential in Industry 4.0. This is clearly evident as continuous tool wear, or worse, sudden machine breakdown, will lead to various manufacturing failures which would clearly cause economic loss. With the availability of deep learning approaches, the great potential and prospect of utilizing these for RUL prediction have resulted in several models which are designed (for RUL prediction) driven by operation data of manufacturing machines. Current efforts in these which are based on fully-supervised models heavily rely on the data labeled with their RULs. However, in these cases, the required RUL prediction data (i.e. the annotated and labeled data from faulty and/or degraded machines) can only be obtained after the machine break-down occurs. The scarcity of broken machines in the modern manufacturing and automation workplace in real- world situations increases the difficulty of getting such sufficient annotated and labeled data. In contrast, the data from healthy machines (and which are currently in operation) is much easier to be collected. Noting this challenge and the potential for improved effectiveness and applicability, we thus propose (and also fully develop) a method based on the idea of masked autoencoders which will utilize unlabeled data to do self-supervision. In thus the work here, a noteworthy masked self-supervised learning approach is developed and utilized; and this is designed to seek to build a deep learning model for RUL prediction by utilizing unlabeled data. The experiments to verify the effectiveness of this development are implemented on the C-MAPSS datasets (which is collected from the data from the NASA turbofan engine). The results rather clearly show that our development and approach here performs better, in both accuracy and effectiveness, for RUL prediction when compared with approaches utilizing a fully- supervised model.
[paper](https://ieeexplore-ieee-org.libproxy1.nus.edu.sg/abstract/document/9976158)

Citation
```
@inproceedings{guo2022masked,
  title={Masked self-supervision for remaining useful lifetime prediction in machine tools},
  author={Guo, Haoren and Zhu, Haiyue and Wang, Jiahui and Vadakkepat, Prahlad and Ho, Weng Khuen and Lee, Tong Heng},
  booktitle={2022 IEEE 20th International Conference on Industrial Informatics (INDIN)},
  pages={353--358},
  year={2022},
  organization={IEEE}
}
```
