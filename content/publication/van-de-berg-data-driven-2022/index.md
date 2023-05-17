---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Data-driven coordination of expensive black-boxes
subtitle: ''
summary: ''
authors:
- Damien van de Berg
- Panagiotis Petsagkourakis
- Nilay Shah
- Ehecatl Antonio del Rio-Chanona
tags:
- Derivative-free optimization
- Expensive black-box
- Surrogate optimization
categories: []
date: '2022-01-01'
lastmod: 2023-05-17T11:58:51+01:00
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
publishDate: '2023-05-17T11:36:44.232352Z'
publication_types:
- '6'
abstract: Coordinating decision-making capacities using optimization is a key factor
  in the success of chemical companies. However, this coordination is often inhibited
  by expensive, legally-constrained, or proprietary subproblem models. We propose
  two variations on how model-based (surrogate) derivative-free optimization (DFO)
  methods can be used to coordinate subproblems with few connecting variables. When
  these surrogates are convex quadratic, they can be efficiently exploited using semidefinite
  programming techniques. We compare the performance of these two variations with
  a distributed optimization solver (ADMM), a model-based, and a direct DFO solver
  (Py-BOBYQA and DIRECTL). This comparison is done on four variations of an economic-environmental
  feedstock blending optimization case study. While ADMM seems to display faster initial
  convergence, explorative DFO optimization solvers seem promising in escaping local
  minimizers, especially in lower dimensions.
publication: '*Computer Aided Chemical Engineering*'
doi: 10.1016/B978-0-323-85159-6.50193-7
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/B9780323851596501937
---
