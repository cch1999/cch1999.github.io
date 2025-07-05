---
title:          "TABASCO: A Fast, Simplified Model for Molecular Generation with Improved Physical Quality"
date:           2024-05-01 00:01:00 +0800
selected:       true
pub:            "ICML GenBio Workshop"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-custom badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
  State-of-the-art models for 3D molecular gen- eration are based on significant inductive bi- ases—SE(3), permutation equivariance to re- spect symmetry and graph message-passing net- works to capture local chemistry—yet the gen- erated molecules still struggle with physical plausibility. We introduce TABASCO which re- laxes these assumptions: The model has a stan- dard non-equivariant transformer architecture, treats atoms in a molecule as sequences and re- constructs bonds deterministically after genera- tion. The absence of equivariant layers and mes- sage passing allows us to significantly simplify the model architecture and scale data through- put. On the GEOM-Drugs benchmark TABASCO achieves state-of-the-art PoseBusters validity and delivers inference roughly 10× faster than the strongest baseline, while exhibiting emergent ro- tational equivariance despite symmetry not be- ing hard-coded. Our work offers a blueprint for training minimalist, high-throughput gener- ative models suited to specialised tasks such as structure- and pharmacophore-based drug de- sign. 
cover:          assets/images/covers/tabasco.png
authors:
  - Miruna Cretu
  - Charles Harris
  - Ilia Igashov
  - Arne Schneuing
  - Marwin Segler
  - Bruno Correia
  - Julien Roy
  - Emmanuel Bengio
  - Pietro Liò
links:
  Paper: https://arxiv.org/abs/2405.01155
  Code: https://github.com/mirunacrt/synflownet
---
