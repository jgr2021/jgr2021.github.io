---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

I am a **PhD Student in Data Science** at **Tsinghua Shenzhen International Graduate School (SIGS), Tsinghua University**, working in **Data Science and Information Technology** under the supervision of **Prof. Ercan Engin Kuruoglu**. My research lies at the intersection of **graph signal processing**, **robust state estimation**, and **statistical signal processing**.

Graph Signal Processing and Time-Varying Graphs
======

My current PhD research focuses on **time-varying graph models** and **graph-based adaptive learning for drone networks**. I am interested in how changing graph structure can represent interactions among distributed agents and how graph-domain information can support filtering, learning, anomaly detection, and decision making in dynamic networks.

More broadly, I am interested in combining model-based signal processing with data-driven learning for networked and multi-agent systems.

Robust State Estimation
======

A major part of my previous and continuing work concerns robust recursive estimation when measurements contain persistent Gaussian background noise together with impulsive or heavy-tailed disturbances.

### Additive Gaussian-Student's t filtering
I developed a robust Kalman-filtering approach that explicitly models measurement noise as the sum of Gaussian and Student's t components. This work appeared at **ICASSP 2026**.

[Publication](/publication/robust-kalman-filter-agst/) · [Code](https://github.com/jgr2021/RKF-AGST)

### Additive Gaussian-GSM filtering
I am extending this idea to a broader **additive Gaussian-Gaussian scale mixture (GSM)** framework. The work introduces a unified model for hybrid measurement noise and develops inference strategies for the resulting latent-scale estimation problem.

[Publication](/publication/robust-kalman-filters-aggsm/) · [Code](https://github.com/jgr2021/RKF-AGGSM)

Statistical Signal Processing
======

My broader interests include statistical modeling, Bayesian inference, and learning for signal processing. I am especially interested in methods that remain reliable under model mismatch, non-Gaussian uncertainty, and changing network structure.

Acoustic signal processing is one application area in which I have used these ideas. During an internship at **Shokz**, I studied microphone-array beamforming and implemented real-time speech-enhancement pipelines in waveform and time-frequency domains. A related patent application studies lightweight real-time speech enhancement for virtual microphone arrays using sparse Bayesian direction estimation, fixed-parameter beamforming, and spectral-domain noise reduction.

Research Themes
======

- Graph signal processing and time-varying graphs
- Robust Bayesian filtering and Kalman-type estimation
- Statistical signal processing and Bayesian inference
- Heavy-tailed and hybrid noise modeling
- Distributed and multi-agent learning
- Microphone arrays, beamforming, and speech enhancement
