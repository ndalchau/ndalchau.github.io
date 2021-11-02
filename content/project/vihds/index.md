---
title: Variational inference for ODE models
summary: "Variational autoencoders can be used to infer hierarchical (global, group-level and individual-level) parameters of  dynamical systems models (ordinary differential equations), and leverages gradient-based optimization"
categories: 
- Bayesian Inference
date: "2018-03-30T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: vi-hds
  url: https://github.com/Biological-Computation/vi-hds
- icon: book
  icon_park: fab
  name: Patent
  url: https://patents.justia.com/patent/11030275
- icon: blog
  icon_park: fab
  name: Microsoft Blog
  url: https://www.microsoft.com/en-us/research/blog/efficient-inference-for-dynamical-models-using-variational-autoencoders/

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

We introduce a flexible, scalable Bayesian inference framework for nonlinear dynamical systems characterised by distinct and hierarchical variability at the individual, group, and population levels. Our model class is a generalisation of nonlinear mixed-effects (NLME) dynamical systems, the statistical workhorse for many experimental sciences. We cast parameter inference as stochastic optimisation of an end-to-end differentiable, block-conditional variational autoencoder. We specify the dynamics of the data-generating process as an ordinary differential equation (ODE) such that both the ODE and its solver are fully differentiable. This model class is highly flexible: the ODE right-hand sides can be a mixture of user-prescribed or "white-box" sub-components and neural network or "black-box" sub-components. Using stochastic optimisation, our amortised inference algorithm could seamlessly scale up to massive data collection pipelines (common in labs with robotic automation). Finally, our framework supports interpretability with respect to the underlying dynamics, as well as predictive generalisation to unseen combinations of group components (also called "zero-shot" learning). We empirically validate our method by predicting the dynamic behaviour of bacteria that were genetically engineered to function as biosensors.
