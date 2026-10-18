---
title: "TractoMFormer: A novel streamline-level tractography analysis framework for group classification using deep graph and multi-scale ViT"
collection: "publications"
permalink: "/publication/tractomformer/"
order: 1
category: "manuscripts"
venue: "NeuroImage"
year: "2026"
publication_status: "Published in"
authors: "**Zixi Wang\\***, Junyi Wang\\*, Yi Pan, Tengfei Xue, Weidong Cai, Yogesh Rathi, Carl-Fredrik Westin, Lauren J. O’Donnell, Fan Zhang"
author_profile: true
note: "* Equal contribution."
---

**Authors:** **Zixi Wang\***, Junyi Wang\*, Yi Pan, Tengfei Xue, Weidong Cai, Yogesh Rathi, Carl-Fredrik Westin, Lauren J. O’Donnell, Fan Zhang

*\* Equal contribution.*

Published in *NeuroImage*, 336 (2026), 121992.

[Paper](https://doi.org/10.1016/j.neuroimage.2026.121992) · [Code](https://github.com/Z-702/mvit_PPMI) · [BibTeX]({{ "/files/tractomformer.bib" | relative_url }})

## Summary

TractoMFormer is a parcellation-free framework for population classification using diffusion MRI tractography at the individual streamline level. Its DTractoEmbedding stage uses a deep graph model to map 3D streamlines into 2D representations that preserve spatial organization and integrate fractional anisotropy, mean diffusivity, and fiber density. A multi-scale vision transformer then analyzes these representations for group classification. Evaluations cover sex classification, schizophrenia versus healthy controls, and Parkinson’s disease versus healthy controls. An attention-based explainability scheme identifies discriminative white matter pathways at the group level.

## 研究简介

TractoMFormer 是一个无需预先进行脑区分割、直接利用单条纤维流线信息开展群体分类的框架。DTractoEmbedding 通过深度图模型将三维纤维流线映射为保留空间关系的二维表示，并融入 FA、MD 和纤维密度等特征。随后，多尺度视觉 Transformer 完成群体分类。研究在性别分类、精神分裂症与健康对照分类、帕金森病与健康对照分类三个任务上进行评估，并利用基于注意力的解释方法识别群体层面具有区分性的白质通路。

## Method

![TractoMFormer framework]({{ "/images/papers/tracto.jpeg" | relative_url }})

*Figure from the corresponding research paper.*
