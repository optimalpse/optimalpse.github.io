---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'ARRTOC: Adversarially Robust Real-Time Optimization and Control'
subtitle: ''
summary: ''
authors:
- Akhil Ahmed
- Ehecatl Antonio del Rio-Chanona
- Mehmet Mercangoz
- akhil
tags:
- Electrical Engineering and Systems Science - Systems and Control
categories: []
date: '2024-03-01'
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
publishDate: '2024-05-18T18:36:02.407226Z'
publication_types:
- '0'
abstract: 'Real-Time Optimization (RTO) plays a crucial role in the process operation
  hierarchy by determining optimal set-points for the lower-level controllers. However,
  at the control layer, these set-points may be difficult to track due to challenges
  in implementation as a result of disturbances, measurement noise, and actuator performance
  limitations. To address this, in this paper, we present the Adversarially Robust
  Real-Time Optimization and Control (ARRTOC) algorithm. ARRTOC addresses this issue
  by finding set-points which are both optimal and inherently robust to implementation
  errors at the control layers. ARRTOC draws inspiration from adversarial machine
  learning, offering a novel constrained Adversarially Robust Optimization (ARO) solution
  applied to the RTO layer. By integrating controller design with RTO, ARRTOC enhances
  overall system performance and robustness by ensuring the chosen set-points are
  tailored to the underlying controller designs. To validate our claims, we present
  three case studies: an illustrative example, a bioreactor case study, and a multi-loop
  evaporator process. The proposed approach is found to improve RTO objectives, such
  as profit, by as much as $50%$ in some case studies compared to RTO formulations
  which ignore the performance of the control layers.'
publication: '*arXiv*'
doi: 10.48550/arXiv.2309.04386
links:
- name: URL
  url: http://arxiv.org/abs/2309.04386
---
