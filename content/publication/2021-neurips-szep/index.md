---
title: "Parameter Inference with Bifurcation Diagrams"
subtitle: ""
summary: ""
authors: 
- Szép G
- Dalchau N
- Csikász-Nagy A


tags: []
categories: [Dynamical Systems, Synthetic Biology]
date: 2021-06-11 00:00:00
publishDate: 2021-06-11 00:00:00
featured: false
draft: false
publication: 'Neural Information Processing Systems (NeurIPS)'
publication_types: ["1"]

url_preprint: 'https://arxiv.org/abs/2106.04243'
abstract: Estimation of parameters in differential equation models can be achieved by applying learning algorithms to quantitative time-series data. However, sometimes it is only possible to measure qualitative changes of a system in response to a controlled condition. In dynamical systems theory, such change points are known as bifurcations and lie on a function of the controlled condition called the bifurcation diagram. In this work, we propose a gradient-based semi-supervised approach for inferring the parameters of differential equations that produce a user-specified bifurcation diagram. The cost function contains a supervised error term that is minimal when the model bifurcations match the specified targets and an unsupervised bifurcation measure which has gradients that push optimisers towards bifurcating parameter regimes. The gradients can be computed without the need to differentiate through the operations of the solver that was used to compute the diagram. We demonstrate parameter inference with minimal models which explore the space of saddle-node and pitchfork diagrams and the genetic toggle switch from synthetic biology. Furthermore, the cost landscape allows us to organise models in terms of topological and geometric equivalence.

projects: []
---