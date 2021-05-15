---
title: "Track, Check, Repeat: An EM Approach to Unsupervised Tracking"
collection: publications
permalink: /publications/EM_track
venue: "The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)"
date: 2021-6-19
citation: 'Adam W. Harley, <b>Yiming Zuo*</b>, Jing Wen*, Ayush Mangal, Shubhankar Potdar, Ritwick Chaudhry, Katerina Fragkiadaki'
---

[[PDF]](http://zuoym15.github.io/files/EM_track.pdf)

## Abstract
We propose an unsupervised method for 3D object segmentation and motion/content disentanglement of unlabelled RGB-D video streams. We isolate the independently-moving foreground under an arbitrary moving camera, split it into trackable components, and track each component in 3D, across partial and full occlusions. The method works by estimating optical flow and egomotion, then iteratively learning 2D and 3D object detectors, and building a motion prior; together these modules form a high-precision tracker. Learning happens in an expectation-maximization framework, where in the expectation step we fire all modules and look for agreement among them, and in the maximization step we re-train the modules to improve this agreement. This iterative process gradually expands recall, until the entire video is explained by tracklets. The constraint of ensemble agreement helps combat contamination of the generated pseudo-labels (during the E step), and standard data augmentation techniques help the modules generalize to yet-unlabelled data (during the M step). We compare against existing unsupervised object discovery and tracking methods, using challenging real-world videos from CATER and KITTI, and show strong improvements over the state-of-the-art.
