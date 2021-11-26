---
title: "Single-DARTS: Towards Stable Architecture Search
"
collection: publications
permalink: /publications/ICCVW21
excerpt: ''
venue: "International Conference on Computer Vision Workshop (ICCVW)"
date: 2021-10-17
paperurl: ''
citation: 'Pengfei Hou*, <b>Ying Jin*</b>, Yukang Chen &quot;Single-DARTS: Towards Stable Architecture Search
&quot;.<i>International Conference on Computer Vision Workshop</i> <b>ICCVW 2021</b>.'
---

[[pdf]](https://openaccess.thecvf.com/content/ICCV2021W/NeurArch/papers/Hou_Single-DARTS_Towards_Stable_Architecture_Search_ICCVW_2021_paper.pdf)

## Abstract
Differentiable architecture search (DARTS) marks a milestone in Neural Architecture Search (NAS), boasting simplicity and small search costs. However, DARTS still suffers from frequent performance collapse, which happens when some operations, such as skip connections, zeroes and poolings, dominate the architecture. In this paper, we are the first to point out that the phenomenon is attributed to bi-level optimization. We propose Single-DARTS which merely uses single-level optimization, updating network weights and architecture parameters simultaneously with the same data batch. Even single-level optimization has been previously attempted, no literature provides a systematic explanation on this essential point. Experiment results show that Single-DARTS achieves state-of-the-art performance on mainstream search spaces. For instance, on NAS-Benchmark-201, the searched architectures are nearly optimal ones. We also validate that the single-level optimization framework is much more stable than the bi-level one. We hope that this simple yet effective method will give some insights on differential architecture search.
