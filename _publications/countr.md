---
title: "CounTr: A Novel End-to-End Transformer Approach for Single Image Crowd Counting"
collection: publications
permalink: /publication/countr
excerpt: 'We introduce CounTr, a novel end-to-end transformer approach for crowd counting and density estimation, which enables capture global context in every layer of the Transformer.'
date: 2022-10-24
venue: 'IWDSC 2022'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Abstract
======
Modeling context information is critical for crowd counting and density estimation. Current prevailing fully-convolutional network (FCN) based crowd counting methods cannot effectively capture long-range dependencies with limited receptive fields. Although recent efforts on inserting dilated convolutions and attention modules have been taken to enlarge the receptive fields, the FCN architecture remains unchanged and retains the fundamental limitation on learning long-range relationships. To tackle the problem, we introduce CounTr, a novel end-to-end transformer approach for crowd counting and density estimation, which enables capture global context in every layer of the Transformer. To be specific, CounTr is composed of a powerful transformer-based hierarchical encoder-decoder architecture. The transformer-based encoder is directly applied to sequences of image patches and outputs multi-scale features. The proposed hierarchical self-attention decoder fuses the features from different layers and aggregates both local and global context features representations. Experimental results show that CounTr achieves state-of-the-art performance on both person and vehicle crowd counting datasets. Particularly, we achieve the first position (159.8 MAE) in the highly crowded UCF_CC_50 benchmark and achieve new SOTA performance (2.0 MAE) in the super large and diverse FDST open dataset. This demonstrates CounTr’s promising performance and practicality for real applications.

Resources
======
[PDF](http://shimmer93.github.io/files/paper1.pdf) Github