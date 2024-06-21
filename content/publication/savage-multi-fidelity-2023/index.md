---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Multi-fidelity data-driven design and analysis of reactor and tube simulations
subtitle: ''
summary: ''
authors:
- tom
- Nausheen Basha
- Jonathan McDonough
- Omar K. Matar
- admin
tags:
- Additive manufacturing
- Bayesian optimization
- Computational fluid dynamics
- Data-driven optimization
- Multi-fidelity
- Reactor design
categories: []
date: '2023-11-01'
lastmod: 2024-05-18T19:36:02+01:00
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
publishDate: '2024-05-18T18:36:02.094290Z'
publication_types:
- '2'
abstract: Optimizing complex reactor geometries is vital to promote enhanced efficiency.
  We present a framework to solve this nonlinear, computationally expensive, and derivative-free
  problem. Gaussian processes are used to learn a multi-fidelity model of reactor
  simulations correlating multiple continuous mesh fidelities. The search space of
  reactor geometries is explored through lower fidelity simulations, evaluated based
  on a weighted acquisition function, trading off information gain with cost. Within
  our framework, DARTS, we derive a novel criteria for dictating optimization termination,
  ensuring a high fidelity solution is returned before budget is exhausted. We investigate
  the design of helical-tube reactors under pulsed-flow conditions, which have demonstrated
  outstanding mixing characteristics. To validate our results, we 3D print and experimentally
  validate the optimal reactor geometry, confirming mixing performance. Our approach
  is applicable to a broad variety of expensive simulation-based optimization problems,
  enabling the design of novel parameterized chemical reactors.
publication: '*Computers & Chemical Engineering*'
doi: 10.1016/j.compchemeng.2023.108410
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0098135423002806
---
