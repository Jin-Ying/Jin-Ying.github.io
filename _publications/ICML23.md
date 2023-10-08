---
title: "Upop: Unified and progressive pruning for compressing vision-language transformers"
collection: publications
permalink: /publications/ICML23
excerpt: ''
venue: "International Conference on Machine Learning (ICML)"
date: 2023-06-23
paperurl: ''
citation: 'Dachuan Shi, Chaofan Tao, <b>Ying Jin</b>, Zhendong Yang, Chun Yuan, Jiaqi Wang
&quot;Upop: Unified and progressive pruning for compressing vision-language transformers.&quot;.<i>International Conference on Machine Learning</i> <b>ICML 2023</b>.'
---

<!-- [[pdf]](https://arxiv.org/abs/2301.07340) -->


## Abstract
Real-world data contains a vast amount of multimodal information, among which vision and language are the two most representative modalities. Moreover, increasingly heavier models, e.g., Transformers, have attracted the attention of researchers to model compression. However, how to compress multimodal models, especially vison-language Transformers, is still under-explored. This paper proposes the Unified and Progressive Pruning (UPop) as a universal vison-language Transformer compression framework, which incorporates 1) unifiedly searching multimodal subnets in a continuous optimization space from the original model, which enables automatic assignment of pruning ratios among compressible modalities and structures; 2) progressively searching and retraining the subnet, which maintains convergence between the search and retrain to attain higher compression ratios. Experiments on multiple generative and discriminative vision-language tasks, including Visual Reasoning, Image Caption, Visual Question Answer, Image-Text Retrieval, Text-Image Retrieval, and Image Classification, demonstrate the effectiveness and versatility of the proposed UPop framework.