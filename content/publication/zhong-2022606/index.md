---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Distributionally Robust MPC for Nonlinear Systems
subtitle: ''
summary: ''
authors:
- Zhengang Zhong
- Ehecatl Antonio del Rio-Chanona
- Panagiotis Petsagkourakis
tags:
- Model predictive control
categories: []
date: '2022-01-01'
lastmod: 2023-05-17T12:15:01+01:00
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
publishDate: '2023-05-17T11:36:44.475287Z'
publication_types:
- '2'
abstract: Classical stochastic model predictive control (SMPC) methods assume that
  the true probability distribution of uncertainties in controlled systems is provided
  in advance. However, in real-world systems, only partial distribution information
  can be acquired for SMPC. The discrepancy between the true distribution and the
  distribution assumed can result in sub-optimality or even infeasibility of the system.
  To address this, we present a novel distributionally robust data-driven MPC scheme
  to control stochastic nonlinear systems. We use distributionally robust constraints
  to bound the violation of the expected state-constraints under process disturbance.
  Sequential linearization is performed at each sampling time to guarantee that the
  system's states comply with constraints with respect to the worst-case distribution
  within the Wasserstein ball centered at the discrete empirical probability distribution.
  Under this distributionally robust MPC scheme, control laws can be efficiently derived
  by solving a conic program. The competence of this scheme for disturbed nonlinear
  systems is demonstrated through two case studies.
publication: '*IFAC-PapersOnLine*'
doi: https://doi.org/10.1016/j.ifacol.2022.07.510
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S2405896322009168
---
