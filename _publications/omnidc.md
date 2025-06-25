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
Depth completion is the task of generating a dense depth map given an image and a sparse depth map as inputs. It has important applications in various downstream tasks. In this paper, we present OGNI-DC, a novel framework for depth completion. The key to our method is "Optimization-Guided Neural Iterations" (OGNI). It consists of a recurrent unit that refines a depth gradient field and a differentiable depth integrator that integrates the depth gradients into a depth map. OGNI-DC exhibits strong generalization, outperforming baselines by a large margin on unseen datasets and across various sparsity levels. Moreover, OGNI-DC has high accuracy, achieving state-of-the-art performance on the NYUv2 and the KITTI benchmarks. Code is available at https://github.com/princeton-vl/OGNI-DC.