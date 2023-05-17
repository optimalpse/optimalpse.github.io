---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Tube-based distributionally robust model predictive control for nonlinear process
  systems via linearization
subtitle: ''
summary: ''
authors:
- Zhengang Zhong
- Ehecatl Antonio del Rio-Chanona
- Panagiotis Petsagkourakis
tags:
- Model predictive control
- Stochastic optimal control
- Uncertain dynamic systems
- Distributionally robust optimization
- Wasserstein ambiguity set
categories: []
date: '2023-01-01'
lastmod: 2023-05-17T12:11:12+01:00
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
publishDate: '2023-05-17T11:36:44.599845Z'
publication_types:
- '2'
abstract: Model predictive control (MPC) is an effective approach to control multivariable
  dynamic systems with constraints. Most real dynamic models are however affected
  by plant-model mismatch and process uncertainties, which can lead to closed-loop
  performance deterioration and constraint violations. Methods such as stochastic
  MPC (SMPC) have been proposed to alleviate these problems; however, the resulting
  closed-loop state trajectory might still significantly violate the prescribed constraints
  if the real system deviates from the assumed disturbance distributions made during
  the controller design. In this work we propose a novel data-driven distributionally
  robust MPC scheme for nonlinear systems. Unlike SMPC, which requires the exact knowledge
  of the disturbance distribution, our scheme decides the control action with respect
  to the worst distribution from a distribution ambiguity set. This ambiguity set
  is defined as a Wasserstein ball centered at the empirical distribution. Due to
  the potential model errors that cause off-sets, the scheme is also extended by leveraging
  an offset-free method. The favorable results of this control scheme are demonstrated
  and empirically verified with a nonlinear mass spring system and a nonlinear CSTR
  case study.
publication: '*Computers & Chemical Engineering*'
doi: https://doi.org/10.1016/j.compchemeng.2022.108112
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0098135422004458
---
