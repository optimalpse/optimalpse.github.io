---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Constrained Reinforcement Learning for Dynamic Optimization under Uncertainty
subtitle: ''
summary: ''
authors:
- P. Petsagkourakis
<<<<<<< HEAD
- I. O. Sandoval
- E. Bradford
- D. Zhang
- E. A. del Rio-Chanona
=======
- ilya
- E. Bradford
- D. Zhang
- admin
>>>>>>> 45fef293bad45213e1e49db40da7d42cc67812b3
tags:
- Reinforcement learning
- Uncertain dynamic systems
- Stochastic control
- Chemical process control
- Adaptive control
- Policy gradient
categories: []
date: '2020-01-01'
lastmod: 2023-05-17T12:36:46+01:00
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
publishDate: '2023-05-17T11:36:46.185469Z'
publication_types:
- '2'
abstract: 'Dynamic real-time optimization (DRTO) is a challenging task due to the
  fact that optimal operating conditions must be computed in real time. The main bottleneck
  in the industrial application of DRTO is the presence of uncertainty. Many stochastic
  systems present the following obstacles: 1) plant-model mismatch, 2) process disturbances,
  3) risks in violation of process constraints. To accommodate these difficulties,
  we present a constrained reinforcement learning (RL) based approach. RL naturally
  handles the process uncertainty by computing an optimal feedback policy. However,
  no state constraints can be introduced intuitively. To address this problem, we
  present a chance-constrained RL methodology. We use chance constraints to guarantee
  the probabilistic satisfaction of process constraints, which is accomplished by
  introducing backoffs, such that the optimal policy and backoffs are computed simultaneously.
  Backoffs are adjusted using the empirical cumulative distribution function to guarantee
  the satisfaction of a joint chance constraint. The advantage and performance of
  this strategy are illustrated through a stochastic dynamic bioprocess optimization
  problem, to produce sustainable high-value bioproducts.'
publication: '*IFAC-PapersOnLine*'
doi: https://doi.org/10.1016/j.ifacol.2020.12.361
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S2405896320306455
---
