---
title: "SPA: A Graph Spectral Alignment Perspective for Domain Adaptation"
collection: publications
permalink: /publications/NeurIPS23
excerpt: ''
venue: "Neural Information Processing Systems (NeurIPS)"
date: 2023-12-01
paperurl: ''
citation: 'Zhiqing Xiao, Haobo Wang, <b>Ying Jin</b>, Lei Feng, Gang Chen, Fei Huang, Junbo Zhao.
&quot;SPA: A Graph Spectral Alignment Perspective for Domain Adaptation.&quot;.<i>Neural Information Processing Systems</i> <b>NeurIPS 2023</b>.'
---

[[pdf]](https://proceedings.neurips.cc/paper_files/paper/2023/file/754e80f98b2a141942f45a0eeb258a3c-Paper-Conference.pdf)


## Abstract
Unsupervised domain adaptation (UDA) is a pivotal form in machine learning to extend the in-domain model to the distinctive target domains where the data distributions differ. Most prior works focus on capturing the inter-domain transferability but largely overlook rich intra-domain structures, which empirically results in even worse discriminability. In this work, we introduce a novel graph SPectral Alignment (SPA) framework to tackle the tradeoff. The core of our method is briefly condensed as follows:(i)-by casting the DA problem to graph primitives, SPA composes a coarse graph alignment mechanism with a novel spectral regularizer towards aligning the domain graphs in eigenspaces;(ii)-we further develop a fine-grained message propagation module---upon a novel neighbor-aware self-training mechanism---in order for enhanced discriminability in the target domain. On standardized benchmarks, the extensive experiments of SPA demonstrate that its performance has surpassed the existing cutting-edge DA methods. Coupled with dense model analysis, we conclude that our approach indeed possesses superior efficacy, robustness, discriminability, and transferability.