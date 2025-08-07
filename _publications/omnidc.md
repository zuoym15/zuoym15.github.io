---
title: "OMNI-DC: Highly Robust Depth Completion with Multiresolution Depth Integration"
collection: publications
permalink: /publications/ognidc
venue: "International Conference on Computer Vision (ICCV)"
date: 2025-10-19
citation: '<b>Yiming Zuo</b>, Willow Yang, Zeyu Ma, Jia Deng'
---

[[PDF]](https://arxiv.org/abs/2406.11711)

## Abstract
Depth completion (DC) aims to predict a dense depth map from an RGB image and sparse depth observations. Existing methods for DC generalize poorly on new datasets or unseen sparse depth patterns, limiting their practical applications. We propose OMNI-DC, a highly robust DC model that generalizes well across various scenarios. Our method incorporates a novel multi-resolution depth integration layer and a probability-based loss, enabling it to deal with sparse depth maps of varying densities. Moreover, we train OMNI-DC on a mixture of synthetic datasets with a scale normalization technique. To evaluate our model, we establish a new evaluation protocol named Robust-DC for zero-shot testing under various sparse depth patterns. Experimental results on Robust-DC and conventional benchmarks show that OMNI-DC significantly outperforms the previous state of the art. The checkpoints, training code, and evaluations are available at https://github.com/princeton-vl/OMNI-DC.