---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Linearizing nonlinear dynamics using deep learning
subtitle: ''
summary: ''
authors:
- Akhil Ahmed
- Ehecatl Antonio del Rio-Chanona
- Mehmet Mercangöz
tags:
- Koopman operator
- Machine learning
- Neural networks
- Nonlinear control
- Nonlinear dynamics
- System identification
categories: []
date: '2023-02-01'
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
publishDate: '2024-05-18T18:36:03.125144Z'
publication_types:
- '2'
abstract: 'The majority of systems of practical interest are characterized by nonlinear
  dynamics. This renders the control and optimization of such systems a complex task
  owing to their nonlinear behaviour. Standard methods of dealing with nonlinear systems
  such as linearizing around a fixed point may not be an effective strategy for many
  systems, thus requiring an alternative approach. For this reason, we propose a novel
  deep learning framework to discover a transformation of a nonlinear dynamical system
  to an equivalent higher dimensional linear system using data generated from identification
  experiments. We demonstrate that the resulting learned linear representation accurately
  captures the dynamics of the original system for a wide range of conditions defined
  by the training dataset used. As a result of this, we show that the learned linear
  model can subsequently be used for the successful control of the original system.
  We demonstrate this by applying the proposed framework to three examples; a benchmark
  example from the literature, and two practical, complex nonlinear dynamical systems
  from the chemical engineering domain: the Continuous Stirred Tank Reactor (CSTR)
  system and finally the four-tank system.'
publication: '*Computers & Chemical Engineering*'
doi: 10.1016/j.compchemeng.2022.108104
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0098135422004379
---
