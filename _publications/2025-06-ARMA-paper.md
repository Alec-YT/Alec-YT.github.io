---
title: "A physics-informed machine learning surrogate model to assess the long-term ground-lining interaction in viscoelastic plastic grounds"
collection: publications
category: conferences
permalink: /publication/2025-06-ARMA-paper
authors:
  - name: "Alec Tristani"
    highlight: true
  - name: "Lina-María Guayacán-Carrillo"
  - name: "Jean Sulem"
header:
  teaser: "publications/2D_model_zoom_in_annotated.png"
excerpt: "A physics-informed machine learning algorithm is developed to predict the long-term ground-lining interaction of deep tunnels. Synthetic data are generated from a 2D plane-strain numerical model, and bagging is applied to the neural network to improve generalization."
date: "2025-06-15"
venue: '59th U.S. Rock Mechanics/Geomechanics Symposium, Santa Fe, New Mexico'
paperurl: 'https://onepetro.org/ARMAUSRMS/proceedings-abstract/ARMA25/ARMA25/786282'
bibtex: |
  @inproceedings{tristani2025physics,
    title={A physics-informed machine learning surrogate model to assess the long-term ground-lining interaction in viscoelastic plastic grounds.},
    author={Tristani, A and Guayac{\'a}n-Carrillo, LM and Sulem, J},
    booktitle={ARMA US Rock Mechanics/Geomechanics Symposium},
    pages={D041S056R001},
    year={2025},
    organization={ARMA},
    doi={https://doi.org/10.56952/ARMA-2025-0533}
  } 
abstract:
  This paper presents a physics-informed machine learning approach for predicting the long-term ground-lining interaction during tunneling. Two-dimensional numerical modeling is performed to generate a synthetic dataset. The rheological model consists of a Zener viscoelastic plastic component (for the deviatoric behavior) and an elastoplastic component (for the volumetric behavior). A Mohr-Coulomb criterion assuming perfect plasticity is used. Instantaneous excavation is assumed, followed by creep activation to simulate the time-dependent effects. Since data is synthetic, a large range of configurations is covered and a random uniform sampling is conducted. An ensemble learning approach is used to enhance the model's generalization by applying the bagging technique to neural networks. The results demonstrate that the ensemble model effectively reduces the variance and achieves lower prediction errors compared to a single model. Furthermore, very good performances are obtained using the relatively scarce dataset. Given its ability to perform fast computations, this machine learning surrogate model could be useful for conducting sensitivity analyses and shows potential for providing real-time assistance during the excavation phase.
---
