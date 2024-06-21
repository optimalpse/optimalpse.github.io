---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Online Feedback Optimization of Compressor Stations with Model Adaptation using
  Gaussian Process Regression
subtitle: ''
summary: ''
authors:
- M. Zagorowska
- M. Degner
- L. Ortmann
- akhil
- S. Bolognani
- admin
- M. Mercangöz
tags:
- Compressors
- Machine learning
- Online Feedback Optimization
- Plant model mismatch
- Process optimization
categories: []
date: '2023-01-01'
lastmod: 2024-05-18T19:36:03+01:00
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
publishDate: '2024-05-18T18:36:03.668246Z'
publication_types:
- '2'
abstract: Online Feedback Optimization is a method used to steer the operation of
  a process plant to its optimal operating point without explicitly solving a nonlinear
  constrained optimization problem. This is achieved by leveraging a linear plant
  model and feedback from measurements. However the presence of plant-model mismatch
  leads to suboptimal results when using this approach. Learning the plant-model mismatch
  enables Online Feedback Optimization to overcome this shortcoming. In this work
  we present a novel application of Online Feedback Optimization with online model
  adaptation using Gaussian process regression. We demonstrate our approach with a
  realistic load sharing problem in a compressor station with parametric and structural
  plant-model mismatch. We assume imperfect knowledge of the compressor maps and design
  an Online Feedback Optimization controller that minimizes the compressor station
  power consumption. In the evaluated scenario, imperfect knowledge of the plant leads
  to a 5% increase in power consumption compared to the case with perfect knowledge.
  We demonstrate that Online Feedback Optimization with model adaptation reduces this
  increase to only 0.8%, closely approximating the case of perfect knowledge of the
  plant, regardless of the type of mismatch.
publication: '*Journal of Process Control*'
doi: 10.1016/j.jprocont.2022.12.001
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0959152422002220
---
