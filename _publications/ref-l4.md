---
title: "Revisiting Referring Expression Comprehension Evaluation in the Era of Large Multimodal Models"
collection: publications
permalink: /publication/ref-l4
excerpt: 'This study identifies limitations in existing REC benchmarks and introduces Ref-L4, a comprehensive benchmark with diverse objects, longer expressions, and a larger vocabulary, to better evaluate modern REC models.'
date: 2025-06-11
venue: 'BEAM (CVPR Workshop)'
citation: 'Chen, J., Wei, F., Zhao, J., Song, S., Wu, B., Peng, Z., Chan, S.G., & Zhang, H. (2024). Revisiting Referring Expression Comprehension Evaluation in the Era of Large Multimodal Models. 2025 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), 513-524.'
---
Abstract
========

Referring expression comprehension (REC) involves localizing a target instance based on a textual description. Recent advancements in REC have been driven by large multimodal models (LMMs) like CogVLM, which achieved 92.44% accuracy on RefCOCO. However, this study questions whether existing benchmarks such as RefCOCO, RefCOCO+, and RefCOCOg, capture LMMs' comprehensive capabilities. We begin with a manual examination of these benchmarks, revealing high labeling error rates: 14% in RefCOCO, 24% in RefCOCO+, and 5% in RefCOCOg, which undermines the authenticity of evaluations. We address this by excluding problematic instances and reevaluating several LMMs capable of handling the REC task, showing significant accuracy improvements, thus highlighting the impact of benchmark noise. In response, we introduce Ref-L4, a comprehensive REC benchmark, specifically designed to evaluate modern REC models. Ref-L4 is distinguished by four key features: 1) a substantial sample size with 45,341 annotations; 2) a diverse range of object categories with 365 distinct types and varying instance scales from 30 to 3,767; 3) lengthy referring expressions averaging 24.2 words; and 4) an extensive vocabulary comprising 22,813 unique words. We evaluate a total of 24 large models on Ref-L4 and provide valuable insights. The cleaned versions of RefCOCO, RefCOCO+, and RefCOCOg, as well as our Ref-L4 benchmark and evaluation code, are available at [this https URL](https://github.com/JierunChen/Ref-L4).

Resources
=========

[Arxiv](https://arxiv.org/abs/2406.16866) [Github](https://github.com/JierunChen/Ref-L4)
