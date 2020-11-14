---
title: "Transferable Normalization: Towards Improving Transferability of Deep Neural Networks."
collection: publications
permalink: /publications/NeurIPS19
excerpt: ''
venue: "Neural Information Processing Systems (NeurIPS)"
date: 2019-12-08
paperurl: ''
citation: 'Ximei Wang, <b>Ying Jin</b>, Mingsheng Long, Jianmin Wang, Michael I.Jordan. &quot;Transferable Normalization: Towards Improving Transferability of Deep Neural Networks&quot;.<i>Neural Information Processing Systems</i> <b>NeurIPS 2019</b>.'
---

[[pdf]](https://papers.nips.cc/paper/2019/file/fd2c5e4680d9a01dba3aada5ece22270-Paper.pdf)
[[code]](https://github.com/thuml/TransNorm)

## Abstract
Deep neural networks (DNNs) excel at learning representations when trained on large-scale datasets. Pre-trained DNNs also show strong transferability when fine-tuned to other labeled datasets. However, such transferability becomes weak when the target dataset is fully unlabeled as in Unsupervised Domain Adaptation (UDA). We envision that the loss of transferability mainly stems from the intrinsic limitation of the architecture design of DNNs. In this paper, we delve into the components of DNN architectures and propose Transferable Normalization (TransNorm) in place of existing normalization techniques. TransNorm is an end-to-end trainable layer to make DNNs more transferable across domains. As a general method, TransNorm can be easily applied to various deep neural networks and domain adaption methods, without introducing any extra hyper-parameters or learnable parameters. Empirical results justify that TransNorm not only improves classification accuracies but also accelerates convergence for mainstream DNN-based domain adaptation methods.