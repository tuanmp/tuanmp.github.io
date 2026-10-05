---
title: "Computational Performance of the ATLAS ITk GNN Track Reconstruction Pipeline"
date: 2024-10-18
lastmod: 2024-10-18
tags: ["Deep Learning","Graph Neural Network","Tracking","ATLAS experiment","Large Hadron Collider","GPU"]
author: [The ATLAS Collaboration]
summary: "We describe a variety of improvements to the algorithmic implementations and machine learning models of the GNN-based track reconstruction pipeline for the ATLAS ITk, significantly decreasing execution times from minutes to hundreds of milliseconds."
editPost:
    URL: "https://cds.cern.ch/record/2914282"
    Text: "ATLAS Note"

---

---

##### Download

+ [Public note](https://cds.cern.ch/record/2914282)

---

##### Abstract

The ATLAS event reconstruction chain is projected to increase dramatically in computational cost with the upgrade to the HL-LHC. A particularly expensive step in this chain is track finding, where energy deposits in the inner tracker (ITk) are grouped into subsets of track candidates, which can then be fitted and provided for downstream tasks. In an effort to reduce execution times and harness accelerator hardware such as GPUs, for both offline and online purposes, machine learning approaches are being developed for track finding. A first functional implementation of a graph neural network-based track pattern reconstruction for ITk has been developed, with competitive physics performance compared with traditional methods. This document describes a variety of improvements to the algorithmic implementations and machine learning models, to significantly decrease execution times from minutes to hundreds of milliseconds.

---

##### Citation

The ATLAS Collaboration. Computational Performance of the ATLAS ITk GNN Track Reconstruction Pipeline. ATL-PHYS-PUB-2024-018, CERN (2024).
Link: [https://cds.cern.ch/record/2914282](https://cds.cern.ch/record/2914282)
