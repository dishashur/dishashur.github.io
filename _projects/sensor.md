---
layout: page
title: Sensor location estimation
description: Signal reconstruction as an inverse problem based on location estimation
img: /assets/img/sen.png
importance: 4
category: 
redirect: false
url: true
---
Inverse problems in localization lead to applications such as SLAM, but this problem was built upon a different perspective. With [Prof. Chandra Murthy](https://eecs.iisc.ac.in/people/chandra-r-murthy/), I explored the problem of estimating a sample’s location using the obtained samples of an 1-D time-invariant field. Having no a priori knowledge of the distribution of the sampling procedure, the objective was to estimate the position of the samples and hence reconstruct the field. While previous work had been carried out in this topic, the goal of my research was to locate the samples with fewer number of samples than had previously been considered. I formulated the objective as an optimization problem. The major challenge is the non-convex nature of the problem, which rendered the gradient-based techniques inefficient. It is in the course of this project that I was introduced to meta-heuristic optimization algorithms. For better insight into the problem's behavior, I implemented a majorization-minimization based algorithm. Along the course, I was introduced to the technique of Finite Rate of Innovation in signals which paints a completely different picture as it uses properties of various transforms to achieve reconstruction.
