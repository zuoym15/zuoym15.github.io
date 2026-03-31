---
title: "Zero-Shot Depth from Defocus"
collection: publications
permalink: /publications/FOSSA
venue: "Arxiv:2603.26658"
date: 2026-03-27
citation: '<b>Yiming Zuo*</b>, Hongyu Wen*, Venkat Subramanian*, Patrick Chen, Karhan Kayan, Mario Bijelic, Felix Heide, Jia Deng (*Equal Contribution)'
---

[[PDF]](https://arxiv.org/abs/2603.26658)

## Abstract
Depth from Defocus (DfD) is the task of estimating a dense metric depth map from a focus stack. Unlike previous works overfitting to a certain dataset, this paper focuses on the challenging and practical setting of zero-shot generalization. We first propose a new real-world DfD benchmark ZEDD, which contains 8.3× more scenes and significantly higher quality images and ground-truth depth maps compared to previous benchmarks. We also design a novel network architecture named FOSSA. FOSSA is a Transformer-based architecture with novel designs tailored to the DfD task. The key contribution is a stack attention layer with a focus distance embedding, allowing efficient information exchange across the focus stack. Finally, we develop a new training data pipeline allowing us to utilize existing large-scale RGBD datasets to generate synthetic focus stacks. Experiment results on ZEDD and other benchmarks show a significant improvement over the baselines, reducing errors by up to 55.7%. The ZEDD benchmark is released athttps://zedd.cs.princeton.edu. The code and checkpoints are released at https://github.com/princeton-vl/FOSSA.