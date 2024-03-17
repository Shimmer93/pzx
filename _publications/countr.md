---
title: "CounTr: A Novel End-to-End Transformer Approach for Single Image Crowd Counting"
collection: publications
permalink: /publication/countr
excerpt: 'We introduce CounTr, a novel end-to-end transformer approach for crowd counting and density estimation, which enables capture global context in every layer of the Transformer.'
date: 2022-10-24
venue: 'IWDSC (ECCV Workshop)'
citation: 'Bai, H., He, H., Peng, Z., Dai, T., Chan, SH.G. (2023). CounTr: An End-to-End Transformer Approach for Crowd Counting and Density Estimation. In: Karlinsky, L., Michaeli, T., Nishino, K. (eds) Computer Vision – ECCV 2022 Workshops. ECCV 2022. Lecture Notes in Computer Science, vol 13806. Springer, Cham. https://doi.org/10.1007/978-3-031-25075-0_16'
---

Abstract
======
Modeling context information is critical for crowd counting and density estimation. Current prevailing fully-convolutional network (FCN) based crowd counting methods cannot effectively capture long-range dependencies with limited receptive fields. Although recent efforts on inserting dilated convolutions and attention modules have been taken to enlarge the receptive fields, the FCN architecture remains unchanged and retains the fundamental limitation on learning long-range relationships. To tackle the problem, we introduce CounTr, a novel end-to-end transformer approach for crowd counting and density estimation, which enables capture global context in every layer of the Transformer. To be specific, CounTr is composed of a powerful transformer-based hierarchical encoder-decoder architecture. The transformer-based encoder is directly applied to sequences of image patches and outputs multi-scale features. The proposed hierarchical self-attention decoder fuses the features from different layers and aggregates both local and global context features representations. Experimental results show that CounTr achieves state-of-the-art performance on both person and vehicle crowd counting datasets. Particularly, we achieve the first position (159.8 MAE) in the highly crowded UCF_CC_50 benchmark and achieve new SOTA performance (2.0 MAE) in the super large and diverse FDST open dataset. This demonstrates CounTr’s promising performance and practicality for real applications.

Resources
======
[Link](https://link.springer.com/chapter/10.1007/978-3-031-25075-0_16)