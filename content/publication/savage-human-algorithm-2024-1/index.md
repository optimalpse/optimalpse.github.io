---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Human-Algorithm Collaborative Bayesian Optimization for Engineering Systems
subtitle: ''
summary: ''
authors:
- tom
- admin
tags:
- Computer Science - Human-Computer Interaction
- Computer Science - Machine Learning
categories: []
date: '2024-04-01'
lastmod: 2024-05-18T19:36:01+01:00
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
publishDate: '2024-05-18T18:36:01.337168Z'
publication_types:
- '0'
abstract: Bayesian optimization has been successfully applied throughout Chemical
  Engineering for the optimization of functions that are expensive-to-evaluate, or
  where gradients are not easily obtainable. However, domain experts often possess
  valuable physical insights that are overlooked in fully automated decision-making
  approaches, necessitating the inclusion of human input. In this article we re-introduce
  the human back into the data-driven decision making loop by outlining an approach
  for collaborative Bayesian optimization. Our methodology exploits the hypothesis
  that humans are more efficient at making discrete choices rather than continuous
  ones and enables experts to influence critical early decisions. We apply high-throughput
  (batch) Bayesian optimization alongside discrete decision theory to enable domain
  experts to influence the selection of experiments. At every iteration we apply a
  multi-objective approach that results in a set of alternate solutions that have
  both high utility and are reasonably distinct. The expert then selects the desired
  solution for evaluation from this set, allowing for the inclusion of expert knowledge
  and improving accountability, whilst maintaining the advantages of Bayesian optimization.
  We demonstrate our approach across a number of applied and numerical case studies
  including bioprocess optimization and reactor geometry design, demonstrating that
  even in the case of an uninformed practitioner our algorithm recovers the regret
  of standard Bayesian optimization. Through the inclusion of continuous expert opinion,
  our approach enables faster convergence, and improved accountability for Bayesian
  optimization in engineering systems.
publication: '*arXiv*'
doi: 10.48550/arXiv.2404.10949
links:
- name: URL
  url: http://arxiv.org/abs/2404.10949
---
