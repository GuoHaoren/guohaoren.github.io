---
title: "Few-Shot Point Cloud Semantic Segmentation for CAM/CAD via Feature Enhancement and Efficient Dual Attention"
collection: publications
category: conferences
permalink: /publication/2023-iecon-cam
excerpt: 'This paper presents a few-shot learning approach for 3D semantic segmentation in CAM/CAD workflows, aimed at improving the segmentation of novel classes in scenarios with high mixture but low volume. The method introduces Sequential Dual Attention (SDA) to capture both channel and spatial features, along with a non-parametric feature enhancement block to improve class recognition in the feature space. Compared to other few-shot models, the proposed approach achieves superior performance across multiple few-shot segmentation scenarios on two datasets, demonstrating significant improvements over baseline methods.'
date: 2023-10-16
venue: 'IECON'
paperurl: 'https://ieeexplore-ieee-org.libproxy1.nus.edu.sg/abstract/document/10311966/'
---
Modern CAM/CAD workflows can benefit greatly from precise 3D semantic segmentation, which contributes to reducing the defect rate of work-pieces manufactured by computer-controlled CNCs and ultimately enhancing work efficiency. The majority of existing approaches for 3D object segmentation heavily rely on fully-supervised learning, where AI models are trained using extensive datasets with annotations. However, these models often exhibit unsatisfactory performance when confronted with scenarios characterized by high mixture but low volume. This means they struggle to accurately segment novel classes that were not encountered during training. In this paper, we introduce and formulate a noteworthy approach based on few-shot learning, which incorporates Sequential Dual Attention (SDA) and feature enhancement techniques. Our method aims to achieve effective semantic segmentation of point clouds in the context of CAM/CAD workflows. Unlike other few-shot models that solely adopt self-attention or lack attention, our SDA captures features at both the channel and spatial levels. Additionally, we design a non-parametric feature enhancement block to enhance the recognizability of each class in the feature space. Our proposed approach consistently demonstrates substantial enhancements in various few-shot point cloud semantic segmentation scenarios across two datasets, outperforming baseline methods.
[paper](https://ieeexplore-ieee-org.libproxy1.nus.edu.sg/abstract/document/10311966/)

Citation
```
@inproceedings{wang2023few,
  title={Few-Shot Point Cloud Semantic Segmentation for CAM/CAD via Feature Enhancement and Efficient Dual Attention},
  author={Wang, Jiahui and Zhu, Haiyue and Guo, Haoren and Al Mamun, Abdullah and De Silva, Clarence W and Lee, Tong Heng},
  booktitle={IECON 2023-49th Annual Conference of the IEEE Industrial Electronics Society},
  pages={1--6},
  year={2023},
  organization={IEEE}
}
```
