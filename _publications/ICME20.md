---
title: "A Multi-Player Minimax Game For Generative Adversarial Networks"
collection: publications
permalink: /publications/ICME20
excerpt: ''
venue: "IEEE International Conference on Multimedia and Expo (ICME)"
date: 2020-07-06
paperurl: ''
citation: 'Ying Jin, Yunbo Wang, Mingsheng Long, Jianmin Wang, Philip S. Yu, Jiaguang Sun. &quot;A Multi-Player Minimax Game For Generative Adversarial Networks&quot;.<i>IEEE International Conference on Multimedia and Expo</i> <b>ICME 2020</b>.'
---

[[pdf]](http://ise.thss.tsinghua.edu.cn/~mlong/doc/multiplayer-gan-icme20.pdf)

## Abstract
While multi-discriminators have been recently exploited to enhance the discriminability and diversity of Generative Adversarial Networks (GANs), these independent discriminators may not collaborate harmoniously to learn diverse and complementary decision boundaries. This paper extends the original two-player adversarial game of GANs by introducing a new multi-player objective named Discriminator Discrepancy Loss (DDL) for diversifying the multi-discriminators. Besides the competition between the generator and each discriminator, there are also competitions between the discriminators: 1) When training multi-discriminators, we simultaneously minimize the original GAN loss and maximize DDL, seeking a good trade-off between the accuracy and diversity. This yields diversified multi-discriminators that fit the generated data distribution to the real data distribution from more comprehensive perspectives. 2) When training the generator, we minimize DDL to encourage the generator to confuse all discriminators. This enhances the diversity of the generated data distribution. Further, we propose a layer-sharing network architecture for the multi-discriminators, which allows them to learn from distinct perspectives about the shared low-level features through better collaboration. It also makes our model more lightweight than existing multi-discriminators approaches. Our DDL-GAN remarkably outperforms other GANs over five standard datasets for image generation tasks.