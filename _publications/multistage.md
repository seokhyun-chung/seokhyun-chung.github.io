---
title: "Federated Condition Monitoring Signal Prediction With Improved Generalization"
collection: publications
permalink: /publication/multistage
excerpt: ''
date: 2022-07-01
venue: 'IEEE Transactions on Automation Science and Engineering'
paperurl: ''
citation: '<b>Chung, S.</b>, Chou, C. H., Fang, X., Al Kontar, R., & Okwudire, C. (2022). A Multi-Stage Approach for Knowledge-Guided Predictions With Application to Additive Manufacturing. <i>IEEE Transactions on Automation Science and Engineering</i>, 19(3), 1675-1687.'
---
Inspired by sequential additive manufacturing operations, we consider prediction tasks arising in processes that comprise of sequential sub-operations and propose a multi-stage inference procedure that exploits prior knowledge of the operational sequence. Our approach decomposes a data-driven model into several easier problems each corresponding to a sub-operation and then introduces a Bayesian inference procedure to quantify and propagate uncertainty across operational stages. We also complement our model with an approach to incorporate physical knowledge of the output of a sub-operation which is often more practical in reality relative to understanding the physics of the entire process. Comprehensive simulations and two case studies on additive manufacturing show that the proposed framework provides well-quantified uncertainties and superior predictive accuracy compared to a single-stage predictive approach. 

<i>Note to Practitioners</i> —This paper is motivated by sequential operations that often occur in manufacturing processes. For example, several additive manufacturing processes consist of multiple sequential steps, e.g., printing, washing, and curing in stereolithography, or printing, debinding, and sintering in binder jetting. In such settings, a complex data-driven model that blindly throws all given data into a single predictive model might not be optimal. To this end, we propose a multi-stage inference procedure that decomposes the problem into easier sub-problem using the prior knowledge of the operational sequence, and propagates uncertainty across stages using Bayesian neural networks. Here we note that even if sequential operations are not existent in reality, one may conceptually decompose a complex system into simpler pieces and exploit our procedure. Also, our approach is able to incorporate physical knowledge of the output of a sub-operation.


[[Link](https://ieeexplore.ieee.org/abstract/document/9743563)]
