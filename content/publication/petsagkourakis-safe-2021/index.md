---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Safe Real-Time Optimization using Multi-Fidelity Gaussian Processes
subtitle: ''
summary: ''
authors:
- Panagiotis Petsagkourakis
- Benoit Chachuat
- Ehecatl Antonio del Rio-Chanona
tags:
- Conferences
- Gaussian processes
- Numerical models
- Real-time systems
- Reliability engineering
- Stochastic systems
- Uncertainty
categories: []
date: '2021-12-01'
lastmod: 2024-05-18T19:36:05+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2024-05-18T18:36:05.428933Z'
publication_types:
- '1'
abstract: This paper proposes a new class of real-time optimization schemes to overcome
  system-model mismatch of uncertain processes. This work’s novelty lies on integrating
  derivative-free optimization schemes and multi-fidelity Gaussian processes within
  a Bayesian optimization framework. The proposed scheme uses two Gaussian processes
  for the stochastic system, one emulates the (known) process model, and another,
  the true system though measurements. In this way, low fidelity samples can be obtained
  via a model, while high fidelity samples are obtained through measurements of the
  system. This framework captures the system’s behavior in a non-parametric fashion,
  while driving exploration through acquisition functions. The benefit of using a
  Gaussian process to represent the system is the ability to perform uncertainty quantification
  in real-time and allow for chance constraints to be satisfied with high confidence.
  This results in a practical approach that is illustrated in numerical case studies,
  including a semi-batch photobioreactor optimization problem.
publication: '*2021 60th IEEE Conference on Decision and Control (CDC)*'
doi: 10.1109/CDC45484.2021.9683599
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/9683599
---
