---
title: "Coarse-to-Fine Joint Registration of MR and Ultrasound Images via Imaging Style Transfer"
collection: "publications"
permalink: "/publication/mr-ultrasound-registration/"
order: 2
category: "conferences"
venue: "ReMIND2Reg / Learn2Reg 2024; arXiv preprint"
year: "2025"
publication_status: "Preprint:"
authors: "Junyi Wang, Xi Zhu, Yikun Guo, **Zixi Wang**, Haichuan Gao, Le Zhang, Fan Zhang"
author_profile: true
---

**Authors:** Junyi Wang, Xi Zhu, Yikun Guo, **Zixi Wang**, Haichuan Gao, Le Zhang, Fan Zhang

ReMIND2Reg / Learn2Reg 2024 work; arXiv preprint, 2025.

[Paper](https://arxiv.org/abs/2508.05240) · [BibTeX]({{ "/files/mr-ultrasound-registration.bib" | relative_url }})

## Summary

This work develops a pipeline to register pre-surgery MR images with post-resection ultrasound images. Unpaired 3D CycleGAN style transfer produces synthetic T1-style images to reduce the appearance gap between modalities. A coarse-to-fine registration strategy then combines affine alignment using block matching with local deformation estimation using SynthMorph. The study reports improved MR–US image consistency in most cases, while also noting that improvements in image-similarity metrics do not always correspond to lower target registration error.

## 研究简介

该研究面向术前磁共振与肿瘤切除后超声影像的配准。首先采用不依赖严格配对数据的 3D CycleGAN，将超声转换为合成的 T1 风格图像，以减小模态间的外观差异；随后结合基于块匹配的仿射配准与 SynthMorph 局部形变估计，完成由粗到精的对齐。研究报告多数情况下影像一致性得到改善，同时指出影像相似性指标的改善并不总能对应更低的目标配准误差。

## Method

![MR–ultrasound registration framework]({{ "/images/papers/registration.png" | relative_url }})

*Figure from the corresponding research paper.*
