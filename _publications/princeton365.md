---
title: "Princeton365: A Diverse Dataset with Accurate Camera Pose"
collection: publications
permalink: /publications/princeton365
venue: "International Conference on Computer Vision (ICCV)"
date: 2025-10-19
citation: 'Karhan Kayan, Stamatis Alexandropoulos, Rishabh Jain, <b>Yiming Zuo</b>, Erich Liang, Jia Deng'
---

[[PDF]](https://arxiv.org/abs/2506.09035)

## Abstract
We introduce Princeton365, a large-scale diverse dataset of 365 videos with accurate camera pose. Our dataset bridges the gap between accuracy and data diversity in current SLAM benchmarks by introducing a novel ground truth collection framework that leverages calibration boards and a 360-camera. We collect indoor, outdoor, and object scanning videos with synchronized monocular and stereo RGB video outputs as well as IMU. We further propose a new scene scale-aware evaluation metric for SLAM based on the the optical flow induced by the camera pose estimation error. In contrast to the current metrics, our new metric allows for comparison between the performance of SLAM methods across scenes as opposed to existing metrics such as Average Trajectory Error (ATE), allowing researchers to analyze the failure modes of their methods. We also propose a challenging Novel View Synthesis benchmark that covers cases not covered by current NVS benchmarks, such as fully non-Lambertian scenes with 360-degree camera trajectories. Please visit https://princeton365.cs.princeton.edu for the dataset, code, videos, and submission.