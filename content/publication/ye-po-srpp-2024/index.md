---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'PO-SRPP: A Decentralized Pivoting Path Planning Method for Self-Reconfigurable
  Satellites'
subtitle: ''
summary: ''
authors:
- Dong Ye
- Bo Wang
- Ligang Wu
- admin
- Zhaowei Sun
tags:
- Faces
- Partially observable systems
- Path planning
- Planning
- Q-learning
- reconfiguration planning
- Satellites
- self-reconfigurable satellite
- Solid modeling
- Task analysis
categories: []
date: '2024-01-01'
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
publishDate: '2024-05-18T18:36:01.450277Z'
publication_types:
- '2'
abstract: While there is ample research on hardware design and reconfiguration control
  for modular self-reconfigurable satellites, relatively few reconfiguration planning
  algorithms, especially algorithms used in real-world reconfiguration have been developed.
  Decentralized path planning, which only uses partial observation for each module
  to make decision is an important problem for real-world task. This article presents
  partially observable self-reconfiguration path planning, addressing the reconfiguration
  path planning problem for a single module using partial observations while aiming
  to maximize the policy learning efficiency. An end-to-end algorithm is proposed
  by employing a recurrent Q-learning algorithm and a deep neural network, where a
  Long Short Term Memory network is used to remember useful features from historical
  observations. Moreover, a 3-D convolutional neural network is used to automatically
  extract high-level features from observation data and is shown to significantly
  increase the learning efficiency. Experiments performed on a test rig of electromagnetic
  self-reconfigurable satellite verified the potency of the proposed algorithm.
publication: '*IEEE Transactions on Industrial Electronics*'
doi: 10.1109/TIE.2024.3370976
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/10475566
---
