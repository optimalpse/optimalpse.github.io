---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Deep Gaussian Process-based Multi-fidelity Bayesian Optimization for Simulated
  Chemical Reactors
subtitle: ''
summary: ''
authors:
- tom
- Nausheen Basha
- Omar Matar
- admin
tags:
- Computer Science - Computational Engineering
- Finance
- and Science
- Computer Science - Machine Learning
categories: []
date: '2022-10-01'
lastmod: 2024-05-18T19:36:04+01:00
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
publishDate: '2024-05-18T18:36:03.971609Z'
publication_types:
- '0'
abstract: New manufacturing techniques such as 3D printing have recently enabled the
  creation of previously infeasible chemical reactor designs. Optimizing the geometry
  of the next generation of chemical reactors is important to understand the underlying
  physics and to ensure reactor feasibility in the real world. This optimization problem
  is computationally expensive, nonlinear, and derivative-free making it challenging
  to solve. In this work, we apply deep Gaussian processes (DGPs) to model multi-fidelity
  coiled-tube reactor simulations in a Bayesian optimization setting. By applying
  a multi-fidelity Bayesian optimization method, the search space of reactor geometries
  is explored through an amalgam of different fidelity simulations which are chosen
  based on prediction uncertainty and simulation cost, maximizing the use of computational
  budget. The use of DGPs provides an end-to-end model for five discrete mesh fidelities,
  enabling less computational effort to gain good solutions during optimization. The
  accuracy of simulations for these five fidelities is determined against experimental
  data obtained from a 3D printed reactor configuration, providing insights into appropriate
  hyper-parameters. We hope this work provides interesting insight into the practical
  use of DGP-based multi-fidelity Bayesian optimization for engineering discovery.
publication: '*arXiv*'
doi: 10.48550/arXiv.2210.17213
links:
- name: URL
  url: http://arxiv.org/abs/2210.17213
---
