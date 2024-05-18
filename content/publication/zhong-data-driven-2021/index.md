---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Data-driven distributionally robust MPC using the Wasserstein metric
subtitle: ''
summary: ''
authors:
- Zhengang Zhong
- Ehecatl Antonio del Rio-Chanona
- Panagiotis Petsagkourakis
tags:
- Electrical Engineering and Systems Science - Systems and Control
- Mathematics - Optimization and Control
categories: []
date: '2021-05-01'
lastmod: 2024-05-18T19:36:05+01:00
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
publishDate: '2024-05-18T18:36:05.223825Z'
publication_types:
- '0'
abstract: A data-driven MPC scheme is proposed to safely control constrained stochastic
  linear systems using distributionally robust optimization. Distributionally robust
  constraints based on the Wasserstein metric are imposed to bound the state constraint
  violations in the presence of process disturbance. A feedback control law is solved
  to guarantee that the predicted states comply with constraints. The stochastic constraints
  are satisfied with regard to the worst-case distribution within the Wasserstein
  ball centered at their discrete empirical probability distribution. The resulting
  distributionally robust MPC framework is computationally tractable and efficient,
  as well as recursively feasible. The innovation of this approach is that all the
  information about the uncertainty can be determined empirically from the data. The
  effectiveness of the proposed scheme is demonstrated through numerical case studies.
publication: '*arXiv*'
doi: 10.48550/arXiv.2105.08414
links:
- name: URL
  url: http://arxiv.org/abs/2105.08414
---
