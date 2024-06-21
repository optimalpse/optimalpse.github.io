---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An Analysis of Multi-Agent Reinforcement Learning for Decentralized Inventory
  Control Systems
subtitle: ''
summary: ''
authors:
- Marwan Mousa
- damin
- niki
- admin
- Max Mowbray
tags:
- Computer Science - Machine Learning
- Computer Science - Multiagent Systems
- Electrical Engineering and Systems Science - Systems and Control
categories: []
date: '2023-07-01'
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
publishDate: '2024-05-18T18:36:02.618288Z'
publication_types:
- '0'
abstract: Most solutions to the inventory management problem assume a centralization
  of information that is incompatible with organisational constraints in real supply
  chain networks. The inventory management problem is a well-known planning problem
  in operations research, concerned with finding the optimal re-order policy for nodes
  in a supply chain. While many centralized solutions to the problem exist, they are
  not applicable to real-world supply chains made up of independent entities. The
  problem can however be naturally decomposed into sub-problems, each associated with
  an independent entity, turning it into a multi-agent system. Therefore, a decentralized
  data-driven solution to inventory management problems using multi-agent reinforcement
  learning is proposed where each entity is controlled by an agent. Three multi-agent
  variations of the proximal policy optimization algorithm are investigated through
  simulations of different supply chain networks and levels of uncertainty. The centralized
  training decentralized execution framework is deployed, which relies on offline
  centralization during simulation-based policy identification, but enables decentralization
  when the policies are deployed online to the real system. Results show that using
  multi-agent proximal policy optimization with a centralized critic leads to performance
  very close to that of a centralized data-driven solution and outperforms a distributed
  model-based solution in most cases while respecting the information constraints
  of the system.
publication: '*arXiv*'
doi: 10.48550/arXiv.2307.11432
links:
- name: URL
  url: http://arxiv.org/abs/2307.11432
---
