---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Constrained model-free reinforcement learning for process optimization
subtitle: ''
summary: ''
authors:
- Elton Pan
- Panagiotis Petsagkourakis
- Max Mowbray
- Dongda Zhang
- Ehecatl Antonio del Rio-Chanona
tags:
- Batch optimization
- data-Driven optimization
- Dynamic systems
- Machine learning
- Process control
- Q-Learning
categories: []
date: '2021-11-01'
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
publishDate: '2024-05-18T18:36:05.328496Z'
publication_types:
- '2'
abstract: Reinforcement learning (RL) is a control approach that can handle nonlinear
  stochastic optimal control problems. However, despite the promise exhibited, RL
  has yet to see marked translation to industrial practice primarily due to its inability
  to satisfy state constraints. In this work we aim to address this challenge. We
  propose an “oracle”-assisted constrained Q-learning algorithm that guarantees the
  satisfaction of joint chance constraints with a high probability, which is crucial
  for safety critical tasks. To achieve this, constraint tightening (backoffs) are
  introduced and adjusted using Broyden’s method, hence making the backoffs self-tuned.
  This results in a methodology that can be imbued into RL algorithms to ensure constraint
  satisfaction. We analyze the performance of the proposed approach and compare against
  nonlinear model predictive control (NMPC). The favorable performance of this algorithm
  signifies a step towards the incorporation of RL into real world optimization and
  control of engineering systems, where constraints are essential.
publication: '*Computers & Chemical Engineering*'
doi: 10.1016/j.compchemeng.2021.107462
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0098135421002404
---
