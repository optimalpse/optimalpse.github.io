---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Chance Constrained Policy Optimization for Process Control and Optimization
subtitle: ''
summary: ''
authors:
- Panagiotis Petsagkourakis
<<<<<<< HEAD
- Ilya Orson Sandoval
- Eric Bradford
- Federico Galvanin
- Dongda Zhang
- Ehecatl Antonio del Rio-Chanona
=======
- ilya
- Eric Bradford
- Federico Galvanin
- Dongda Zhang
- admin
>>>>>>> 45fef293bad45213e1e49db40da7d42cc67812b3
tags:
- Policy search
- Reinforcement Learning
- Data-driven process control
- Chance constraints
- Bayesian Optimization
categories: []
date: '2022-01-01'
lastmod: 2023-05-17T12:08:16+01:00
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
publishDate: '2023-05-17T11:36:44.722985Z'
publication_types:
- '2'
abstract: Chemical process optimization and control are affected by (1) plant-model
  mismatch, (2) process disturbances, and (3) constraints for safe operation. Reinforcement
  learning by policy optimization would be a natural way to solve this due to its
  ability to address stochasticity, plant-model mismatch, and directly account for
  the effect of future uncertainty and its feedback in a proper closed-loop manner;
  all without the need of an inner optimization loop. One of the main reasons why
  reinforcement learning has not been considered for industrial processes (or almost
  any engineering application) is that it lacks a framework to deal with safety critical
  constraints. Present algorithms for policy optimization use difficult-to-tune penalty
  parameters, fail to reliably satisfy state constraints or present guarantees only
  in expectation. We propose a chance constrained policy optimization (CCPO) algorithm
  which guarantees the satisfaction of joint chance constraints with a high probability
  — which is crucial for safety critical tasks. This is achieved by the introduction
  of constraint tightening (backoffs), which are computed simultaneously with the
  feedback policy. Backoffs are adjusted with Bayesian optimization using the empirical
  cumulative distribution function of the probabilistic constraints, and are therefore
  self-tuned. This results in a general methodology that can be imbued into present
  policy optimization algorithms to enable them to satisfy joint chance constraints
  with high probability. We present case studies that analyse the performance of the
  proposed approach.
publication: '*Journal of Process Control*'
doi: https://doi.org/10.1016/j.jprocont.2022.01.003
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0959152422000038
---
