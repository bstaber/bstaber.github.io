---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I'm a research scientist in machine learning at the research center of Safran, a french company that designs and manufactures various aerospace and defense equipments. I specialize in machine learning on graph data and I have a strong interest in uncertainty quantification. Developing scientific codes is also an area that I particularly enjoy.

In 2018, I defended my [PhD thesis](https://theses.hal.science/tel-01982185) on uncertainty quantification in computational mechanics and was awarded a [European PhD award](https://www.eccomas.org/2019/10/15/eccomas-award-for-the-best-ph-d-theses-of-2018-on-computational-methods-in-applied-sciences-and-engineering/) for my work. Since then, I have been working as a machine learning researcher with a focus on applying my expertise to the field of aeronautics. I spend my time working on Bayesian inference and conformal predictions for uncertainty quantification, as well as kernel methods and deep learning for surrogate modeling.

Research interests
==================

* Uncertainty quantification in ML (Bayesian inference, ensemble techniques, conformal predictions)
* Machine learning for graphes (graph neural networks, graph kernels, optimal transport, ...)
* Kernel methods for post-processing MCMC outputs 
* Stochastic modeling in computational mechanics

Softwares
=========

* [kernax (coming soon)](https://gitlab.com/drti/kernax) : python package that implements a regularized variant of the Stein thinning algorithm, written with JAX
* [batorch](https://gitlab.com/drti/batorch) : python package that implements a few stochastic gradient MCMC methods for Bayesian neural networks with PyTorch and Hydra
* [TrilinosUQComp](https://github.com/bstaber/TrilinosUQComp) : C++ library I developped as a graduate student and which implements a parallel finite element method thanks to Trilinos (linearized & finite strain elasticity), together with a few sampling algorithms for non Gaussian random fields (spectral and SPDE pproaches)

Publications
============

The list of my preprints and publications can also be found on [Google Scholar](https://scholar.google.fr/citations?user=61j2VawAAAAJ&hl=fr&oi=ao).

Prepints
---------

* B. Staber, S. Da Veiga, Benchmarking Bayesian neural networks and metrics for regression tasks ([arXiv:2206.06779](https://arxiv.org/abs/2206.06779))
* C. Benard, B. Staber, S. Da Vegiga, Kernel Stein Discrepancy thinning: a theoretical perspective of pathologies and a practical fix with regularization ([arXiv:2301.13528](https://arxiv.org/pdf/2301.13528.pdf))

Published papers
----------------

* B. Staber, S. Forest, M. Al-Kotob, M. Mazière, T. Tose, Loss of ellipticity analysis in non-smooth plasticity, IJSS (2021) ([hal-03372375](https://hal.science/hal-03372375/document))
* B. Staber, J. Guilleminot, C. Soize, J. Michopoulos, A. Iliopoulos, Stochastic modeling and identification of a hyperelastic constitutive model for laminated composites, CMAME (2019) ([sciencedirect](https://www.sciencedirect.com/science/article/abs/pii/S0045782518306431))
* B. Staber, J. Guilleminot, A random field model for anisotropic strain energy functions and its application for uncertainty quantification in vascular mechanics, CMAME (2018à ([sciencedirect](https://www.sciencedirect.com/science/article/abs/pii/S0045782518300033))
* B. Staber, J. Guilleminot, Stochastic modeling and generation of random fields of elasticity tensors: a unified information-theoretic approach, CRM (2017) ([sciencedirect](https://www.sciencedirect.com/science/article/pii/S1631072117300773))
* B. Staber, J. Guilleminot, Stochastic hyperelastic constitutive laws and identification procedure for soft biological tissues with intrinsic variability, JMBBM (2017) ([hal-01367381](https://hal.science/hal-01367381/file/JMBBM-Preprint.pdf))
* B. Staber, J. Guilleminot, Stochastic modeling of the Ogden class of stored energy functions for hyperelastic materials: the compressible case, ZAMM-Journal of Applied Mathemarics and Mechanics (2017) ([wiley](https://onlinelibrary.wiley.com/doi/abs/10.1002/zamm.201500255))
* B. Staber, J. Guilleminot, Functional approximation and projection of stored energy functions in computational homogenization of hyperelastic materials: A probabilistic perspective, CMAME (2017) ([sciencedirect](https://www.sciencedirect.com/science/article/abs/pii/S0045782516303103))
* B. Staber, J. Guilleminot, Stochastic modeling of a class of stored energy functions for incompressible hyperelastic materials with uncertainties, CRM (2015) ([sciencedirect](https://www.sciencedirect.com/science/article/pii/S1631072115000832))
* B. Staber, J. Guilleminot, Approximate solutions of Lagrange multipliers for information-theoretic random field models, SIAM/JUQ (2015) ([hal-01166830](https://hal.science/hal-01166830/document))
