---
title:          "Diffusion-Free Graph Generation with Next-Scale Prediction"
date:           2025-06-01 00:01:00 +0800
selected:       False
pub:            "ICML GenBio Workshop"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-custom badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
 Here, we propose MAG, a novel diffusion-free graph generation framework based on next-scale prediction. By leveraging a hierarchy of latent representations, the model proogressively generates scales of the entire graph without the need for explicit node ordering.
cover:          assets/images/covers/next_scale.png
authors:
  - Samuel Belkadi
  - Steve Hong
  - Marian Chen
  - Miruna Cretu
  - Charles Harris
  - Pietro Liò
links:
  Paper: https://arxiv.org/pdf/2503.23612?
---




Samuel Belkadi * 1 Steve Hong * 1 Marian Chen * 1 Abstract
1. Introduction
Graphs provide a natural and flexible information represen- tation across a wide range of domains, including social net- works, biological and molecular structures, recommender systems, and infrastructural networks. Consequently, the ability to learn a graph distribution from data and generate realistic graphs is pivotal for applications such as network science, drug discovery, and protein design.
Despite significant progress in generative models for lan-
* Equal contribution 1 Department of Engineering, University of Cambridge, UK 2Department of Computer Science, Univer- sity of Cambridge, UK. Correspondence to: Samuel Belkadi <sb2764@cam.ac.uk>, Steve Hong <mdh58@cam.ac.uk>.
Proceedings of the 42nd International Conference on Machine Learning, Vancouver, Canada. PMLR 267, 2025. Copyright 2025 by the author(s).
Miruna Cretu 2 Charles Harris 2 Pietro Lio` 2