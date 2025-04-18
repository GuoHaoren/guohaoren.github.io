---
title: "Enhancing Multivariate Time-Series Domain Adaptation via Contrastive Frequency Graph Discovery and Language-Guided Adversary Alignment"
collection: publications
category: conferences
authors: 'Haoren Guo, Haiyue Zhu, Jiahui Wang, Vadakkepat Prahlad, Weng Khuen Ho, Tong Heng Lee'
permalink: /publications/ConFGD
excerpt: 'Unsupervised domain adaptation (UDA) minimizes reliance on labeled data by aligning features between a labeled source domain and an unlabeled target domain, making it effective for multivariate time series (MTS) prediction. Existing MTS UDA methods often overlook inter-series dependencies and frequency-domain insights. To address this, the proposed Frequency Graph Discovery (FGD) module uncovers shared frequency information, while the Frequency-Contextual Contrastive Learning (FCCL) framework aligns frequency-contextual representations for label-invariant prediction. Additionally, the Language-guided Adversary Alignment (LAA) module leverages large language models (LLMs) to enhance alignment using text-encoded labeled embeddings. This approach achieves state-of-the-art results on public MTS datasets.'
date: 2024-12-08
venue: 'The Thirty-Ninth AAAI Conference on Artificial Intelligence (AAAI-25)'
paperurl: 'https://aaai.org/conference/aaai/aaai-25/'
---

Abstract:
Unsupervised domain adaptation (UDA) is a machine learning approach designed to minimize reliance on labeled data by aligning features between a labeled source domain and an unlabeled target domain, thereby reducing feature discrepancies, which is efficient for multivariate time series (MTS) prediction. However, most MTS UDA methods focus solely on aligning intra-series temporal features, overlooking the valuable information in inter-series dependencies. Research has highlighted that analyzing decomposed frequency dependencies in time series can reveal significant trends, noise patterns, and intricate temporal details.
To address these unexplored frequency dependencies, we introduce the Frequency Graph Discovery Module (FGD), which uncovers and aligns shared frequency information and correlations across domains. Additionally, we propose a Frequency-Contextual Contrastive Learning (FCCL) framework to better capture and align frequency-contextual representations in multivariate time series, ensuring the extraction of label-invariant information for prediction. Furthermore, considering existing models overlooking the valuable and abundant information outside source and target dataset, we enhance the MTS UDA prediction model with a Language-guided Adversary Alignment (LAA) module, which leverages the advancement and capabilities of Large Language Models (LLMs) to get text-encoded labeled embeddings and align the classification features, thereby improving prediction accuracy.
Our model achieves state-of-the-art results on three public multivariate time-series datasets for unsupervised domain adaptation, as demonstrated by empirical results.

[pdf (Main + APPENDIX)](../files/aaai_2025_ghr.pdf)
