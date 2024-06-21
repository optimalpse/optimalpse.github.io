---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Data-driven coordination of subproblems in enterprise-wide optimization under
  organizational considerations
subtitle: ''
summary: ''
authors:
- damien
- Panagiotis Petsagkourakis
- Nilay Shah
- admin
tags:
- coordination
- data-driven optimization
- distributed optimization
- expensive black-box
categories: []
date: '2023-01-01'
lastmod: 2023-05-17T11:58:53+01:00
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
publishDate: '2023-05-17T11:36:45.448935Z'
publication_types:
- '2'
abstract: 'While decomposition techniques in mathematical programming are usually
  designed for numerical efficiency, coordination problems within enterprise-wide
  optimization are often limited by organizational rather than numerical considerations.
  We propose a “data-driven” coordination framework which manages to recover the same
  optimum as the equivalent centralized formulation while allowing coordinating agents
  to retain autonomy, privacy, and flexibility over their own objectives, constraints,
  and variables. This approach updates the coordinated, or shared, variables based
  on derivative-free optimization (DFO) using only coordinated variables to agent-level
  optimal subproblem evaluation “data.” We compare the performance of our framework
  using different DFO solvers (CUATRO, Py-BOBYQA, DIRECT-L, GPyOpt) against conventional
  distributed optimization (ADMM) on three case studies: collaborative learning, facility
  location, and multiobjective blending. We show that in low-dimensional and nonconvex
  subproblems, the exploration-exploitation trade-offs of DFO solvers can be leveraged
  to converge faster and to a better solution than in distributed optimization.'
publication: '*AIChE Journal*'
doi: 10.1002/aic.17977
links:
- name: URL
  url: https://onlinelibrary.wiley.com/doi/abs/10.1002/aic.17977
---
