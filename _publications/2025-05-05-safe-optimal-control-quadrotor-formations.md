---
title: "Safe Optimal Control of Quadrotor Formations Using Multilayer Neural Networks and Continual Learning"
collection: publications
category: manuscripts
permalink: /publication/2025-05-05-safe-optimal-control-quadrotor-formations
excerpt: 
date: 2025-05-05
venue: "International Journal of Adaptive Control and Signal Processing"
slidesurl:                  # add URL if you have slides
paperurl: "https://onlinelibrary.wiley.com/doi/full/10.1002/acs.4020"                     # add DOI or link if available
bibtexurl: 
citation:
---
**Keywords:** Barrier Lyapunov Function, Formation Control, Multilayer Neural Networks, Optimal Control, Singular Value Decomposition (SVD), Continual Learning.

### Abstract

This article presents an integral reinforcement learning–based optimal formation tracking scheme for multiple quadrotor unmanned aerial vehicles (QUAVs) experiencing nonlinear coupled dynamics and subject to constraints. We use multilayer neural networks (MNN) within an actor–critic framework where the MNN weights are tuned using singular value decomposition (SVD) of the activation-function gradient to approximate the optimal control policy via backstepping. Additionally, barrier Lyapunov functions (BLF) are introduced to ensure set invariance—keeping the quadrotors within a defined safety envelope despite disturbances. A novel weight-update law for each layer is derived using the HJB approximation error and control-input error, and stabilizing terms from Lyapunov analysis enhance output-layer stability. To mitigate catastrophic forgetting in multitasking missions, online continual learning is incorporated at every layer. The method is demonstrated on leader–follower formations using spherical coordinates, showing improved tracking accuracy and robustness over traditional schemes.


