---
title: "Multi-level Logit Distillation"
collection: publications
permalink: /publications/CVPR23
excerpt: ''
venue: "Computer Vision and Pattern Recognition Conference (CVPR)"
date: 2023-03-25
paperurl: ''
citation: '<b>Ying Jin</b>, Jiaqi Wang, Dahua Lin
&quot;Multi-level Logit Distillation.&quot;.<i>Computer Vision and Pattern Recognition Conference</i> <b>CVPR 2023</b>.'
---

<!-- [[pdf]](https://arxiv.org/abs/2301.07340) -->


## Abstract
Knowledge Distillation (KD) aims at distilling the knowledge from the large teacher model to a lightweight student model. Mainstream KD methods can be divided into two categories, logit distillation, and feature distillation. The former is easy to implement, but inferior in performance, while the latter is not applicable to some practical circumstances due to concerns such as privacy and safety. Towards this dilemma, in this paper, we explore a stronger logit distillation method via making better utilization of logit outputs. Concretely, we propose a simple yet effective approach to logit distillation via \textbf{multi-level prediction alignment}. Through this framework, the prediction alignment is not only conducted at the \textit{instance} level, but also at the \textit{batch} and \textit{class} level, through which the student model learns instance prediction, input correlation, and category correlation simultaneously. In addition, a prediction augmentation mechanism based on model calibration further boosts the performance. Extensive experiment results validate that our method enjoys consistently higher performance than previous logit distillation methods, and even reaches competitive performance with mainstream feature distillation methods.