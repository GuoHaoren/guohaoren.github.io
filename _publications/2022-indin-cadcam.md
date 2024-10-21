---
title: "CAM/CAD Point Cloud Part Segmentation via Few-Shot Learning"
collection: publications
category: conferences
permalink: /publication/2022-indin-cadcam
excerpt: '3D part segmentation plays a critical role in improving the efficiency and reducing defects in CAM/CAD manufacturing workflows, particularly for CNC machinery. Traditional segmentation methods rely on fully-supervised learning, which requires large annotated datasets and struggles to generalize to new segmentation tasks. To address these limitations, the authors propose a few-shot learning approach that improves generalization and flexibility by using fewer samples. Their method, inspired by the attMPTI network, incorporates a multi-prototype approach with self-attention, along with transform net and center loss block, to better capture 3D features while reducing storage space and enhancing processing efficiency.'
date: 2022-07-15
venue: 'INDIN'
paperurl: 'https://ieeexplore-ieee-org.libproxy1.nus.edu.sg/abstract/document/9976119'
---

3D part segmentation is an essential step in advanced CAM/CAD workflow. Precise 3D segmentation contributes to lower defective rate of work-pieces produced by the manufacturing equipment (such as computer controlled CNCs), thereby improving work efficiency and attaining the attendant economic benefits. A large class of existing works on 3D model segmentation are mostly based on fully-supervised learning, which trains the AI models with large, annotated datasets. However, the disadvantage is that the resulting models from the fully-supervised learning methodology are highly reliant on the completeness (or otherwise) of the available dataset, and its generalization ability is relatively poor to new unknown/unseen segmentation types (i.e., further additional so-called novel classes). In this work, we propose and develop a noteworthy few-shot learning-based approach for effective part segmentation in CAM/CAD; and this is designed to significantly enhance its generalization ability, and our development also aims to flexibly adapt to new segmentation tasks by using only relatively rather few samples. As a result, it not only reduces the requirements for the usually unattainable and exhaustive completeness of supervision datasets, but also improves the flexibility for real-world applications. In the development, drawing inspiration from the pertinent and interesting work described in the open literature as the attMPTI network, we propose and develop a multi-prototype approach (with self-attention mechanics) for few-shot point cloud part segmentation. As further improvement and innovation, we additionally adopt the transform net and the center loss block in the network. These characteristics serve to improve the comprehension for 3D features of the various possible instances of the whole work-piece and ensure the close distribution of the same class in feature space. Moreover, our approach stores data in the point cloud format that reduces space consumption, and which also makes the various procedures involved have significantly easier read and edit access (thus improving efficiency and effectiveness and lowering costs).
[Paper](https://ieeexplore-ieee-org.libproxy1.nus.edu.sg/abstract/document/9976119)

Citation:
```
@inproceedings{wang2022cam,
  title={Cam/cad point cloud part segmentation via few-shot learning},
  author={Wang, Jiahui and Zhu, Haiyue and Guo, Haoren and Al Mamun, Abdullah and Vadakkepat, Prahlad and Lee, Tong Heng},
  booktitle={2022 IEEE 20th International Conference on Industrial Informatics (INDIN)},
  pages={359--365},
  year={2022},
  organization={IEEE}
}
```
