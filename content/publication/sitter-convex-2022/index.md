---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Convex Q-learning: Reinforcement learning through convex programming'
subtitle: ''
summary: ''
authors:
- Sophie Sitter
- Damien van de Berg
- Max Mowbray
- Antonio del Rio Chanona
- Panagiotis Petsagkourakis
tags:
- convex Q-learning
- data-driven batch optimization
- dynamic process control
- machine learning
- semi-definite programming
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
publishDate: '2023-05-17T11:36:44.354769Z'
publication_types:
- '6'
abstract: Over the last decade, Reinforcement Learning (RL) has received significant
  attention as it promises novel and efficient solutions to complex control problems.
  This work builds on model-free RL, namely Q-learning, to determine optimal control
  policies for nonlinear, complex biochemical processes. We propose convex functions
  instead of deep neural networks as state-action value function approximators to
  reduce computational complexity. A convex Q-function surrogate is trained using
  semidefinite programming. The surrogate is then minimized to determine the optimal
  control action. This results in 75.3% lower computational time compared with deep
  Q-networks. By alleviating the computational burden of traditional RL approximation
  functions, this work addresses one of the major obstacles for the successful implementation
  of RL to real-world engineering applications.
publication: '*Computer Aided Chemical Engineering*'
doi: 10.1016/B978-0-323-85159-6.50056-7
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/B9780323851596500567
---
