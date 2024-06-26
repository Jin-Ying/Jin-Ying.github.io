---
title: "Minimum Class Confusion for Versatile Domain Adaptation."
collection: publications
permalink: /publications/ECCV20
excerpt: ''
venue: "European Conference on Computer Vision (ECCV)"
date: 2020-08-23
paperurl: ''
citation: '<b>Ying Jin</b>, Ximei Wang, Mingsheng Long, Jianmin Wang. &quot;Minimum Class Confusion for Versatile Domain Adaptation&quot;.<i>European Conference on Computer Vision</i> <b>ECCV 2020</b>.'
---

[[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660460.pdf)
[[code]](https://github.com/thuml/Versatile-Domain-Adaptation)

## Abstract
There are a variety of Domain Adaptation (DA) scenarios subject to label sets and domain configurations, including closed-set and partial-set DA, as well as multi-source and multi-target DA. It is notable that existing DA methods are generally designed only for a specific scenario, and may underperform for scenarios they are not tailored to. To this end, this paper studies Versatile Domain Adaptation (VDA), where one method can handle several different DA scenarios without any modification. Towards this goal, a more general inductive bias other than the domain alignment should be explored. We delve into a missing piece of existing methods: class confusion, the tendency that a classifier confuses the predictions between the correct and ambiguous classes for target examples, which is common in different DA scenarios. We uncover that reducing such pairwise class confusion leads to significant transfer gains. With this insight, we propose a general loss function: Minimum Class Confusion (MCC). It can be characterized as (1) a non-adversarial DA method without explicitly deploying domain alignment, enjoying faster convergence speed; (2) a versatile approach that can handle four existing scenarios: Closed-Set, Partial-Set, Multi-Source, and Multi-Target DA, outperforming the state-of-the-art methods in these scenarios, especially on one of the largest and hardest datasets to date (7.3% on DomainNet). Its versatility is further justified by two scenarios proposed in this paper: Multi-Source Partial DA and Multi-Target Partial DA. In addition, it can also be used as a general regularizer that is orthogonal and complementary to a variety of existing DA methods, accelerating convergence and pushing these readily competitive methods to stronger ones. Code is available at https://github.com/thuml/Versatile-Domain-Adaptation.