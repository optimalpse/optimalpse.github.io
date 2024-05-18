---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Investigating physics-informed neural networks for bioprocess hybrid model
  construction
subtitle: ''
summary: ''
authors:
- Alexander William Rogers
- Ilya Orson Sandoval Cardenas
- Ehecatl Antonio Del Rio-Chanona
- Dongda Zhang
tags:
- automatic model structure identification
- hybrid modelling
- machine learning
- physics-informed neural network
- time-varying parameter estimation
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
publishDate: '2024-05-18T18:36:03.348881Z'
publication_types:
- '6'
abstract: Integrating physical knowledge and machine learning is a cost-efficient
  solution to modelling complex biochemical processes when the underlying mechanisms
  are not fully understood. However, hybrid model structure identification is still
  time-consuming for new processes, ruiring iteration over different hypotheses to
  explain the observed process dynamics while minimizing over-parameterization. Unfortunately,
  conventional approaches to automatic model structure identification do not always
  converge for highly nonlinear models and cannot estimate time-varying model parameters.
  To address this and accelerate the design of new biochemical processes, a Reinforcement
  Learning (RL) based framework recently reformulated synchronous hybrid model structure-parameter
  identification into a process optimal control problem. To further investigate other
  possible solutions, in this study, a novel Physics Informed Neural Network (PINN)
  based framework was proposed for the first time to infer time-varying kinetic parameters.
  This framework first combines possible kinetic structures from phenomenological
  knowledge, then simultaneously identifies the most likely hybrid model structure
  and time-varying parameter trajectories. To demonstrate the performance of the PINN
  based framework, several in-silico case studies were conducted using a known ground
  truth bioprocess. We thoroughly examined the advantages and limitations of the framework,
  elucidating its potential for high-fidelity hybrid model construction in biochemical
  engineering research.
publication: '*Computer Aided Chemical Engineering*'
doi: 10.1016/B978-0-443-15274-0.50014-7
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/B9780443152740500147
---
