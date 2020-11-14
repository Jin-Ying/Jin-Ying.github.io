---
title: "Transferring Pretrained Networks to Small Data via Category Decorrelation."
collection: publications
permalink: /publications/BMVC20
excerpt: ''
venue: "British Machine Vision Conference (BMVC)"
date: 2020-09-07
paperurl: ''
citation: '<b>Ying Jin*</b>, Zhangjie Cao*, Mingsheng Long, Jianmin Wang. &quot;Minimum Class Confusion for Versatile Domain Adaptation&quot;.<i>British Machine Vision Conference</i> <b>BMVC 2020</b>.'
---

[[pdf]](https://www.bmvc2020-conference.com/assets/papers/0090.pdf)

## Abstract
Transfer learning by fine-tuning neural networks pre-trained on large-scale datasets excels at accelerating the training process and improving the model performance for the target task. Previous works have unveiled catastrophic forgetting in fine-tuning, where the model is over-transferred thus losing pre-trained knowledge, especially facing large- scale target dataset. However, when fine-tuning pre-trained networks to small data, under transfer emerges instead, where the model sticks to the pre-trained model and learns little target knowledge. Under transfer severely restricts the wide use of fine-tuning but is still under-investigated. In this paper, we conduct an in-depth study of under transfer problem in fine-tuning and observe that when we finetune model to small data, redundant category correlation becomes stronger in the model prediction, which is a potential cause of under transfer. Based on the observation, we propose a novel regularization approach, Category Decorrelation (CatDec), to minimize category correlation in the model, which introduces a new inductive bias to strengthen the model transfer. Cat-Dec is orthogonal to existing fine-tuning approaches and can collaborate with them to address the dilemma of catastrophic forgetting and under transfer. Experiment results demonstrate that the proposed approach can consistently improve the fine-tuning performance of various mainstream methods. Further analyses prove that CatDec alleviates redundant category correlation and helps transfer.