---
title: "Hierarchical Graph Neural Networks for Particle Track Reconstruction"
date: 2023-03-03
lastmod: 2026-01-01
tags: ["Deep Learning","Graph Neural Network","Tracking","Machine Learning","Large Hadron Collider"]
author: [R. Liu, P. Calafiura, S. Farrell, X. Ju, D. T. Murnane, "T. M. Pham"]
summary: "We introduce a novel variant of GNN for particle tracking called Hierarchical Graph Neural Network (HGNN), together with a learnable pooling algorithm (GMPool) and a dedicated loss function, showing improved tracking efficiency and robustness over traditional GNNs."
editPost:
    URL: "https://arxiv.org/abs/2303.01640"
    Text: "arXiv"

---

---

##### Download

+ [Preprint](https://arxiv.org/abs/2303.01640)
+ Published in [J. Phys. Conf. Ser. 3206 (2026) 012084](https://doi.org/10.1088/1742-6596/3206/1/012084)

---

##### Abstract

We introduce a novel variant of GNN for particle tracking called Hierarchical Graph Neural Network (HGNN). The architecture creates a set of higher-level representations which correspond to tracks and assigns spacepoints to these tracks, allowing disconnected spacepoints to be assigned to the same track, as well as multiple tracks to share the same spacepoint. We propose a novel learnable pooling algorithm called GMPool to generate these higher-level representations called "super-nodes", as well as a new loss function designed for tracking problems and HGNN specifically. On a standard tracking problem, we show that, compared with previous ML-based tracking algorithms, the HGNN has better tracking efficiency performance, better robustness against inefficient input graphs, and better convergence compared with traditional GNNs.

---

##### Citation

R. Liu, P. Calafiura, S. Farrell, X. Ju, D. T. Murnane, T. M. Pham. Hierarchical Graph Neural Networks for Particle Track Reconstruction. arXiv:2303.01640 (2023); J. Phys. Conf. Ser. 3206 (2026) 012084.
Link: [https://arxiv.org/abs/2303.01640](https://arxiv.org/abs/2303.01640)
