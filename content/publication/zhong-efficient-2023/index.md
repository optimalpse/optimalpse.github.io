---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An efficient data-driven distributionally robust MPC leveraging linear programming
subtitle: ''
summary: ''
authors:
- zhengang
- admin
- Panagiotis Petsagkourakis
tags:
- Additives
- Costs
- Linear programming
- Linear systems
- Optimal control
- Springs
- Statistical learning
categories: []
date: '2023-05-01'
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
publishDate: '2024-05-18T18:36:02.719893Z'
publication_types:
- '1'
abstract: This paper presents a distributionally robust data-driven model predictive
  control (MPC) framework for discrete-time linear systems with additive disturbances,
  while assuming the distribution is only partially known through samples. The corresponding
  optimal control problem considers a distributionally robust (DR) objective over
  an ambiguity set of estimated disturbance expectations. A statistical learning bound
  is provided to validate the ambiguity set. For this control problem, polytopic hard
  input constraints and state chance constraints are considered. State chance constraints
  are formulated into linear deterministic constraints through solving a DR optimization
  problem with Wasserstein ambiguity set. The resulting optimal control problem can
  be equivalently solved by a linear program. We prove recursive feasibility and provide
  an average asymptotic cost bound for the corresponding MPC framework. The method
  is compared, demonstrated and analysed on a mass spring control example.
publication: '*2023 American Control Conference (ACC)*'
doi: 10.23919/ACC55779.2023.10156224
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/10156224
---
