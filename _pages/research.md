---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research lies at the intersection of **statistical signal processing**, **state estimation**, and **graph-based learning**. I am particularly interested in methods that remain reliable under model mismatch, non-Gaussian uncertainty, and changing network structure.

Robust State Estimation
======

A major part of my work concerns robust recursive estimation when measurements contain both persistent Gaussian background noise and impulsive disturbances.

### Additive Gaussian-Student's t filtering
I developed a robust Kalman-filtering approach that explicitly models measurement noise as the sum of Gaussian and Student's t components. This work appeared at **ICASSP 2026**.

[Publication](/publication/robust-kalman-filter-agst/) · [Code](https://github.com/jgr2021/RKF-AGST)

### Additive Gaussian-GSM filtering
I am extending this idea to a broader **additive Gaussian-Gaussian scale mixture (GSM)** framework. The work introduces a unified model for hybrid measurement noise and develops inference strategies for the resulting latent-scale estimation problem.

[Publication](/publication/robust-kalman-filters-aggsm/) · [Code](https://github.com/jgr2021/RKF-AGGSM)

Graph Signal Processing and Time-Varying Graphs
======

My current research direction includes **time-varying graph models** and **graph-based adaptive learning for drone networks**. I am interested in how graph structure can be used to represent interactions among distributed agents and how graph-domain information can support filtering, learning, and anomaly-aware decision making in dynamic networks.

This direction builds on my broader interest in combining model-based signal processing with learning methods for networked systems.

Acoustic Signal Processing
======

I have also worked on practical acoustic signal processing for microphone arrays and wearable devices. During an internship at **Shokz**, I studied beamforming and implemented real-time speech-enhancement pipelines in waveform and time-frequency domains.

A related patent application studies a lightweight real-time speech-enhancement method for virtual microphone arrays using sparse Bayesian direction estimation, fixed-parameter beamforming, and spectral-domain noise reduction.

Research Themes
======

- Robust Bayesian filtering and Kalman-type estimation
- Heavy-tailed and hybrid noise modeling
- Graph signal processing and time-varying graphs
- Distributed and multi-agent learning
- Microphone arrays, beamforming, and speech enhancement
