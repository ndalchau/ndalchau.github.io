---
title: "Efficient Amortised Bayesian Inference for Hierarchical and Nonlinear Dynamical Systems"
subtitle: ""
summary: "Conference Paper (ICML): Introduces the methodology of using variational autoencoders to inference hierarchically assigned parameters of ordinary differential equation (ODE) models"
authors: 
- Roeder G
- Grant PK
- Phillips A
- Dalchau N
- Meeds E


tags: []
categories: [Bayesian Inference, Dynamical Systems, Synthetic Biology]
date: 2019-06-09 00:00:00
publishDate: 2019-06-09 00:00:00
featured: true
draft: false
publication: 'International Conference on Machine Learning (ICML)'
publication_types: ["1"]
url_preprint: 'https://arxiv.org/abs/1905.12090'
links:
- icon: github
  icon_pack: fab
  name: Github
  url: https://github.com/Biological-Computation/vi-hds

abstract: We introduce a flexible, scalable Bayesian inference framework for nonlinear dynamical systems characterised by distinct and hierarchical variability at the individual, group, and population levels. Our model class is a generalisation of nonlinear mixed-effects (NLME) dynamical systems, the statistical workhorse for many experimental sciences. We cast parameter inference as stochastic optimisation of an end-to-end differentiable, block-conditional variational autoencoder. We specify the dynamics of the data-generating process as an ordinary differential equation (ODE) such that both the ODE and its solver are fully differentiable. This model class is highly flexible&#58; the ODE right-hand sides can be a mixture of user-prescribed or &quot;white-box&quot; sub-components and neural network or &quot;black-box&quot; sub-components. Using stochastic optimisation, our amortised inference algorithm could seamlessly scale up to massive data collection pipelines (common in labs with robotic automation). Finally, our framework supports interpretability with respect to the underlying dynamics, as well as predictive generalization to unseen combinations of group components (also called &quot;zero-shot&quot; learning). We empirically validate our method by predicting the dynamic behaviour of bacteria that were genetically engineered to function as biosensors.

projects: [VI-HDS]
---