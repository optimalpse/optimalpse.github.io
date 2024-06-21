---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Hierarchical planning-scheduling-control -- Optimality surrogates and derivative-free
  optimization
subtitle: ''
summary: ''
authors:
- damien
- Nilay Shah
- admin
tags:
- Computer Science - Computational Engineering
- Finance
- and Science
- Mathematics - Optimization and Control
categories: []
date: '2023-10-01'
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
publishDate: '2024-05-18T18:36:02.199379Z'
publication_types:
- '0'
abstract: Planning, scheduling, and control typically constitute separate decision-making
  units within chemical companies. Traditionally, their integration is modelled sequentially,
  but recent efforts prioritize lower-level feasibility and optimality, leading to
  large-scale, potentially multi-level, hierarchical formulations. Data-driven techniques,
  like optimality surrogates or derivative-free optimization, become essential in
  addressing ensuing tractability challenges. We demonstrate a step-by-step workflow
  to find a tractable solution to a tri-level formulation of a multi-site, multi-product
  planning-scheduling-control case study. We discuss solution tractability-accuracy
  trade-offs and scaling properties for both methods. Despite individual improvements
  over conventional heuristics, both approaches present drawbacks. Consequently, we
  synthesize our findings into a methodology combining their strengths. Our approach
  remains agnostic to the level-specific formulations when the linking variables are
  identified and retains the heuristic sequential solution as fallback option. We
  advance the field by leveraging parallelization, hyperparameter tuning, and a combination
  of off- and on-line computation, to find tractable solutions to more accurate multi-level
  formulations.
publication: '*arXiv*'
doi: 10.48550/arXiv.2310.07870
links:
- name: URL
  url: http://arxiv.org/abs/2310.07870
---
