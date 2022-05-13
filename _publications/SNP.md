---
title: "View Synthesis with Sculpted Neural Points"
collection: publications
permalink: /publications/SNP
venue: "arXiv:2205.05869"
date: 2022-5-12
citation: '<b>Yiming Zuo</b>, Jia Deng'
---

[[PDF]](https://arxiv.org/pdf/2205.05869)

## Abstract
We address the task of view synthesis, which can be posed as recovering a rendering function that renders new views from a set of existing images.  In many recent works such as NeRF, this rendering function is parameterized using implicit neural representations of scene geometry. Implicit neural representations have achieved impressive visual quality but have drawbacks in computational efficiency. In this work, we propose a new approach that performs view synthesis using point clouds. It is the first point-based method to achieve better visual quality than NeRF while being more than 100x faster in rendering speed. Our approach builds on existing works on differentiable point-based rendering but introduces a novel technique we call ``Sculpted Neural Points (SNP)'', which significantly improves the robustness to errors and holes in the reconstructed point cloud. Experiments show that on the task of view synthesis, our sculpting technique closes the gap between point-based and implicit representation-based methods. Code is available at https://github.com/princeton-vl/SNP and supplementary video at https://youtu.be/ctPBhvgVOow.