---
title: "Single Domain Generalization for Crowd Counting"
collection: publications
permalink: /publication/mpcount
excerpt: 'We propose MPCount to tackle the problem of regression nature and label ambiguity for single domain generalization for crowd counting.'
date: 2024-06-19
venue: 'CVPR'
citation: 'Single Domain Generalization for Crowd Counting, Zhuoxuan Peng, S.-H. Gary Chan, Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024'
---

Abstract
======
Current image-based crowd counting widely employs density map regression due to its promising results. However, the method often suffers from severe performance degradation when tested on data from unseen scenarios. To address this so-called "domain shift" problem, we investigate single domain generalization (SDG) for crowd counting. The existing SDG approaches are mainly for classification and segmentation, and can hardly be extended to our case due to its regression nature and label ambiguity (i.e., ambiguous pixel-level ground truths). We propose MPCount, a novel SDG approach effective even for narrow source distribution. Reconstructing diverse features for density map regression with a single memory bank, MPCount retains only domain-invariant representations using a content error mask and attention consistency loss. It further introduces patch-wise classification as an auxiliary task to boost the robustness of density prediction to achieve highly accurate labels. Through extensive experiments on different datasets, MPCount is shown to significantly improve counting accuracy compared to the state-of-the-art approaches under diverse scenarios unobserved in the training data of narrow source distribution.

Resources
======
[Arxiv](https://arxiv.org/abs/2403.09124) [Github](https://github.com/Shimmer93/MPCount)