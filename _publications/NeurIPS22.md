---
title: "Semi-Supervised Semantic Segmentation via Gentle Teaching Assistant."
collection: publications
permalink: /publications/NeurIPS22
excerpt: ''
venue: "Neural Information Processing Systems (NeurIPS)"
date: 2022-12-01
paperurl: ''
citation: '<b>Ying Jin</b>, Jiaqi Wang, Dahua Lin
&quot;Semi-Supervised Semantic Segmentation via Gentle Teaching Assistant.&quot;.<i>Neural Information Processing Systems</i> <b>NeurIPS 2022</b>.'
---

<!-- [[pdf]](https://papers.nips.cc/paper/2021/file/8a1e808b55fde9455cb3d8857ed88389-Paper.pdf) -->


## Abstract
<!-- Object detection has achieved substantial progress in the last decade. However, detecting novel classes with only few samples remains challenging, since deep learning under low data regime usually leads to a degraded feature space. Existing works employ a holistic fine-tuning paradigm to tackle this problem, where the model is first pre-trained on all base classes with abundant samples, and then it is used to carve the novel class feature space. Nonetheless, this paradigm is still imperfect. Durning fine-tuning, a novel class may implicitly leverage the knowledge of multiple base classes to construct its feature space, which induces a scattered feature space, hence violating the inter-class separability. To overcome these obstacles, we propose a two-step fine-tuning framework, Few-shot object detection via Association and DIscrimination (FADI), which builds up a discriminative feature space for each novel class with two integral steps. 1) In the association step, in contrast to implicitly leveraging multiple base classes, we construct a compact novel class feature space via explicitly imitating a specific base class feature space. Specifically, we associate each novel class with a base class according to their semantic similarity. After that, the feature space of a novel class can readily imitate the well-trained feature space of the associated base class. 2) In the discrimination step, to ensure the separability between the novel classes and associated base classes, we disentangle the classification branches for base and novel classes. To further enlarge the inter-class separability between all classes, a set-specialized margin loss is imposed. Extensive experiments on standard Pascal VOC and MS-COCO datasets demonstrate that FADI achieves new state-of-the-art performance, significantly improving the baseline in any shot/split by +18.7. Notably, the advantage of FADI is most announced on extremely few-shot scenarios (e.g. 1- and 3- shot). -->
Stay tuned!