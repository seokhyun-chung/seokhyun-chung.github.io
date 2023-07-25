---
title: "Federated Multi-output Gaussian Processes"
collection: publications
permalink: /publication/fedmgp
excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2015-10-01
venue: 'Technometrics'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'Chung, S., & Kontar, R. (2023) &quot;Federated Multi-output Gaussian Processes,&quot; <i>Technometrics</i>, DOI: 10.1080/00401706.2023.2238834.'
---
Multi-output Gaussian process (MGP) regression plays an important role in the integrative analysis of different but interrelated systems/units. Existing MGP approaches assume that data from all units is collected and stored at a central location. This requires massive computing and storage power at the central location, induces significant communication traffic due to raw data exchange, and comprises privacy of units. However, recent advances in Internet of Things technologies, which have tremendously increased edge computing power, pose a significant opportunity to address such challenges. In this paper, we propose FedMGP, a general federated analytics (FA) framework to learn an MGP in a decentralized manner that utilizes edge computing power to distribute model learning efforts. Specifically, we propose a hierarchical modeling approach where an MGP is built upon shared global latent functions. We then develop a variational inference FA algorithm that overcomes the need to share raw data. Instead, collaborative learning is achieved by only sharing global latent function statistics. Comprehensive simulation studies and the case study on battery degradation data highlight the superior predictive performance and versatility of FedMGP, achieved while distributing computing and storage demands, reducing communication burden, fostering privacy, and personalizing analysis.

[[Link](https://www.tandfonline.com/doi/full/10.1080/00401706.2023.2238834)]
