---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Integrating process design and control using reinforcement learning
subtitle: ''
summary: ''
authors:
- Steven Sachio
- Max Mowbray
- Maria M. Papathanasiou
- Ehecatl Antonio del Rio-Chanona
- Panagiotis Petsagkourakis
tags:
- Bilevel optimization
- Optimal design
- Policy gradient
- Process control
- Reinforcement learning
categories: []
date: '2022-07-01'
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
publishDate: '2024-05-18T18:36:04.078652Z'
publication_types:
- '2'
abstract: To create efficient-high performing processes, one must find an optimal
  design with its corresponding controller that ensures optimal operation in the presence
  of uncertainty. When comparing different process designs, for the comparison to
  be meaningful, each design must involve its optimal operation. Therefore, to optimize
  a process’ design, one must address design and control simultaneously. For this,
  one can formulate a bilevel optimization problem, with the design as the outer problem
  in the form of a mixed-integer nonlinear program (MINLP) and a stochastic optimal
  control as the inner problem. This is intractable by most approaches. In this paper
  we propose to compute the optimal control using reinforcement learning, and then
  embed this controller into the design problem. This allows to decouple the solution
  procedure, while having the same optimal result as if solving the bilevel problem.
  The approach is tested in two case studies and the performance of the controller
  is evaluated. The case studies indicate that the proposed approach outperforms current
  state-of-the-art simultaneous design and control strategies. This opens a new avenue
  to address simultaneous design and control of engineering systems.
publication: '*Chemical Engineering Research and Design*'
doi: 10.1016/j.cherd.2021.10.032
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0263876221004421
---
