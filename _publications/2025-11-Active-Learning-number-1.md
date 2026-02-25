---
title: "Active learning with physics-informed neural networks for optimal sensor placement in deep tunneling through transversely isotropic elastic rocks"
collection: publications
category: manuscripts
permalink: /publication/2025-11-15-paper-title-number-2
excerpt: 'Active learning'
date: 2025-11-15
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2511.20574'
citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
This paper presents a deep learning strategy to simultaneously solve Partial Differential Equations (PDEs) and back-calculate their parameters in the context of deep tunnel excavation. A Physics-Informed Neural Network (PINN) model is trained with synthetic data that emulates in situ displacement measurements in the host rock and at the cavity wall, obtained from extensometers and convergence monitoring. As acquiring field observations can be costly, a sequential training approach based on active learning is implemented to determine the most informative locations for new sensors. In particular, Monte Carlo dropout is used to quantify epistemic uncertainty and query measurements in regions where the model is least confident. This approach reduces the amount of required field data and optimizes sensor placement. The PINN is tested to reconstruct the displacement field around a deep tunnel of circular section excavated in transversely isotropic elastic rock and to determine rock constitutive and stress-field parameters. Results demonstrate excellent performance on small, scattered, and noisy datasets, achieving high precision for the Young's moduli, shear modulus, horizontal-to-vertical far-field stress ratio, and the orientation of the bedding planes. The proposed framework shall ultimately support decision-making for optimal subsurface monitoring and for adaptive tunnel design and control.
