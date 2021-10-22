---
title: Chemical Reaction Networks
summary: Tools for programming chemical reaction networks (CRN), DNA strand-displacement circuits (DSD) and genetically engineered circuits (GEC)
categories:
- Dynamical Systems
- DNA Computing
- Synthetic Biology
date: "2013-01-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: crn-engine
  url: https://github.com/BiologicalComputation/crn-engine

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

Chemical Reaction Networks Engine (CRN-Engine) is an open source repository that enables programming and analysis of (bio)chemical systems. 

The implementation for several domain-specific programming languages (DSLs) are included, and have been published previously in web tools and the scientific literature: 
- [Visual DSD](https://classicdsd.azurewebsites.net)
- [Visual GEC](https://classicgec.azurewebsites.net)
- [Visual CRN](https://visualcrn.azurewebsites.net)

The languages compile to *chemical reaction networks*, which is a mathematical object that defines parameterised chemical systems. Several analysis methods are provided, which can be applied to all CRN-compatible languages:
- Stochastic simulation (Gillespie's Direct Method)
- Moment closure techniques (Approximate simulation of stochastic dynamics)
- Integration of the chemical master equation
- Satisfiability analysis for stable systems, using the [Z3 theorem prover](https://github.com/Z3Prover/z3)
- Parameter inference from observation data, using Markov chain Monte Carlo (MCMC).