---
title: "Data-Driven Tools to Evaluate Support Pressure, Radial Displacements, and Face Extrusion for Tunnels Excavated in Elastoplastic Grounds"
category: manuscripts
permalink: /publication/2024-11-15-test
collection: publications
category: manuscripts
authors:
- name: "Alec Tristani"
  Hightligh = True
- name: "Lina-Mar{\'\i}a Guayac{\'a}n-Carrillo"
- name: "Jean Sulem"
header:
  teaser: "publications/bagging.png"
excerpt: 'A methodology is presented for training machine learning surrogate models in the context of tunneling. In particular, bagging is applied to neural networks and synthetic datasets are created to predict the ground-lining interaction as well as the extrusion of the face of deep tunnels excavated in elastoplastic grounds.'
date: 2024-11-15
venue: 'International Journal for Numerical and Analytical Methods in Geomechanics'
paperurl: 'https://onlinelibrary.wiley.com/doi/full/10.1002/nag.3889'
demourl: 'https://huggingface.co/spaces/AlecT/Tunnels'
bibtex: |
  @article{tristani2025data,
    title={Data-Driven Tools to Evaluate Support Pressure, Radial Displacements, and Face Extrusion for Tunnels Excavated in Elastoplastic Grounds},
    author={Tristani, Alec and Guayac{\'a}n-Carrillo, Lina-Mar{\'\i}a and Sulem, Jean},
    journal={International Journal for Numerical and Analytical Methods in Geomechanics},
    doi = {https://doi.org/10.1002/nag.3889},
    volume={49},
    number={2},
    pages={654--664},
    year={2025},
    publisher={Wiley Online Library}
  }
abstract: |
 Two-dimensional analysis of tunnel design based on the convergence–confinement method, although commonly used in tunnel design, may not always be applied. For example, in squeezing grounds, if the support is installed very close to the tunnel face, three-dimensional numerical modeling is required but is computationally expensive. Therefore, it is usually performed before or after tunnel excavation. A machine learning approach is presented here as an alternative to costly computations. Two surrogate models are developed based on synthetic data. The first model aims to assess the support pressure and the radial displacement at equilibrium in the lining and the radial displacement occurring close to the face at the installation distance of the support. The second model is intended to compute the extrusion of the core considering an unlined gallery. It is assumed a circular tunnel excavated in a Mohr–Coulomb elastoplastic perfectly plastic ground under an initial isotropic stress state. In particular, the bagging method is applied to neural networks to enhance the generalization capability of the models. A good performance is obtained using relatively scarce datasets. The modeling of the surrogate models is explained from the creation of the synthetic datasets to the evaluation of their performance. Their limitations are discussed. In practice, these two machine learning tools should be helpful in the field during the excavation phase.
---
