---
title: "Seeing and Seeing Through the Glass: Real and Synthetic Data for Multi-Layer Depth Estimation"
collection: publications
permalink: /publications/layereddepth
venue: "arXiv Preprint"
date: 2025-03-14
citation: 'Hongyu Wen, <b>Yiming Zuo</b>, Venkat Subramanian, Patrick Chen, Jia Deng'
---

[[PDF]](https://arxiv.org/pdf/2503.11633)

## Abstract
Transparent objects are common in daily life, and understanding their multi-layer depth information -- perceiving both the transparent surface and the objects behind it -- is crucial for real-world applications that interact with transparent materials. In this paper, we introduce LayeredDepth, the first dataset with multi-layer depth annotations, including a real-world benchmark and a synthetic data generator, to support the task of multi-layer depth estimation. Our real-world benchmark consists of 1,500 images from diverse scenes, and evaluating state-of-the-art depth estimation methods on it reveals that they struggle with transparent objects. The synthetic data generator is fully procedural and capable of providing training data for this task with an unlimited variety of objects and scene compositions. Using this generator, we create a synthetic dataset with 15,300 images. Baseline models training solely on this synthetic dataset produce good cross-domain multi-layer depth estimation. Fine-tuning state-of-the-art single-layer depth models on it substantially improves their performance on transparent objects, with quadruplet accuracy on our benchmark increased from 55.14% to 75.20%. All images and validation annotations are available under CC0 at https://layereddepth.cs.princeton.edu.