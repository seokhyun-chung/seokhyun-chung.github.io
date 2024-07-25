---
title: "Federated Automatic Latent Variable Selection in Multi-output Gaussian Processes"
collection: publications
permalink: /publication/real-time
excerpt: ''
date: 2024-07-25
venue: 'ArXiv'
paperurl: ''
citation: 'Gao, Jingyi & <b>Chung, S.</b> (2024). Federated Automatic Latent Variable Selection in Multi-output Gaussian Processes. arXiv preprint arXiv:2407.16935.'
---

This paper explores a federated learning approach that automatically selects the number of latent processes in multi-output Gaussian processes (MGPs). The MGP has seen great success as a transfer learning tool when data is generated from multiple sources/units/entities. A common approach in MGPs to transfer knowledge across units involves gathering all data from each unit to a central server and extracting common independent latent processes to express each unit as a linear combination of the shared latent patterns. However, this approach poses key challenges in (i) determining the adequate number of latent processes and (ii) relying on centralized learning which leads to potential privacy risks and significant computational burdens on the central server. To address these issues, we propose a hierarchical model that places spike-and-slab priors on the coefficients of each latent process. These priors help automatically select only needed latent processes by shrinking the coefficients of unnecessary ones to zero. To estimate the model while avoiding the drawbacks of centralized learning, we propose a variational inference-based approach, that formulates model inference as an optimization problem compatible with federated settings. We then design a federated learning algorithm that allows units to jointly select and infer the common latent processes without sharing their data. We also discuss an efficient learning approach for a new unit within our proposed federated framework. Simulation and case studies on Li-ion battery degradation and air temperature data demonstrate the advantageous features of our proposed approach.

[Link](https://arxiv.org/abs/2407.16935)
