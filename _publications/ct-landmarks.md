---
title: "A Novel Dimension-Reduction Method Combining HRNet Projection with Volumetric Depth Recovery for Robust Facial Landmark Detection in CT Scans"
collection: "publications"
permalink: "/publication/ct-landmarks/"
order: 3
category: "submitted"
venue: "Artificial Intelligence in Medicine"
year: ""
publication_status: "Submitted to"
authors: "Xiwen Yu, Junyi Wang, Jincan Zhu, **Zixi Wang**, Lipeng Ning, Guoqiang Xie, Fan Zhang"
author_profile: true
---

**Authors:** Xiwen Yu, Junyi Wang, Jincan Zhu, **Zixi Wang**, Lipeng Ning, Guoqiang Xie, Fan Zhang

Manuscript submitted to *Artificial Intelligence in Medicine*.

## Summary

This manuscript presents a Dimension-Reduction-Recovery framework for 3D facial landmark localization in head CT. CT volumes are projected into frontal pseudocolor images, where HRNet heatmap regression and sub-pixel refinement localize 2D landmarks. A constrained ray-wise search using Hounsfield units and gradient cues recovers volumetric depth. On 150 clinical CT scans with 98 landmarks per scan, the manuscript reports a mean radial error of 1.97 mm and a 92.4% success detection rate at a 4 mm threshold.

## 研究简介

这篇稿件提出用于头部 CT 三维面部标志点定位的“降维—恢复”框架：将 CT 体积投影为正面伪彩图，通过 HRNet 热图回归及亚像素细化定位二维标志点，再结合 HU 值和梯度约束，沿射线搜索恢复三维深度。在 150 例临床 CT、每例 98 个标志点的实验中，稿件报告平均径向误差为 1.97 mm，4 mm 阈值内的成功检测率为 92.4%。

## Method

![CT landmark detection framework]({{ "/images/papers/landmarks.jpeg" | relative_url }})

*Figure from the corresponding research paper.*
