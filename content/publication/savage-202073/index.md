---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An adaptive data-driven modelling and optimization framework for complex chemical
  process design
subtitle: ''
summary: ''
authors:
- tom
- Hector Fernando Almeida-Trasvina
- admin
- Robin Smith
- Dongda Zhang
tags:
- large-scale chemical process
- surrogate modelling
- dimensionality reduction
- Gaussian processes
- artificial neural network
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
publishDate: '2023-05-17T11:36:46.430167Z'
publication_types:
- '6'
abstract: Current advances in computer-aided chemical process design and synthesis
  take advantage of surrogate modelling and superstructure optimization techniques.
  Conventionally, this is completed by using first-principle physical models or data-driven
  models to replace the original rigorous models for optimization and selection of
  a specific unit operation. Despite its achievements, this strategy is inefficient
  when dealing with complex process flowsheets such as utility and refrigeration systems
  where a large number of unit operations are heavily connected by recycling streams.
  To address this problem, an integrated data-driven modelling and optimization framework
  is proposed in this work. The framework first constructs a hybrid machine learning
  based surrogate model to automatically reduce the system dimensionality and capture
  the nonlinearity of the underlying chemical process. Then, an efficient optimization
  algorithm, in specific, evolutionary algorithm, is embedded to identify the optimal
  solution of this surrogate model. Quality and accuracy of the estimated optimal
  solution is finally validated against the rigorous process model. Through an iterative
  approach, optimal operating conditions for the entire process flowsheet are efficiently
  identified. Furthermore, the novel CryoMan Cascade cycle system for large scale
  liquefied natural gas manufacturing is used as the case study. This framework is
  demonstrated to be superior regarding time-efficiency, solution quality, and flexibility
  over the rigorous model based optimization approach.
publication: '*30th European Symposium on Computer Aided Process Engineering*'
doi: https://doi.org/10.1016/B978-0-12-823377-1.50013-6
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/B9780128233771500136
---
