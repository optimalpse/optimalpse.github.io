---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Model-free safe reinforcement learning for chemical processes using Gaussian
  processes
subtitle: ''
summary: ''
authors:
- Thomas Savage
- Dongda Zhang
- Max Mowbray
- Ehecatl Antonio Del Río Chanona
tags:
- Batch Processes
- Modelling
- Identification
- Scheduling
- Optimization
categories: []
date: '2021-01-01'
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
publishDate: '2023-05-17T11:36:46.061278Z'
publication_types:
- '2'
abstract: Model-free reinforcement learning has been recently investigated for use
  in chemical process control. Through the iterative creation of an approximate process
  model, control actions are able to be explored and optimal policies generated. Typically,
  this approximate process model has taken the form of a neural network that is continuously
  updated. However when small quantities of historical data are available, for example
  in novel processes, neural networks tend to over-fit to data providing poor performance.
  In this paper Gaussian processes are used as a method of function approximation
  to describe the action-value function of a non-isothermal semi-batch reactor. Through
  the use of analytical uncertainty obtained from Gaussian process predictions, trade
  off between exploration and exploitation is enabled, allowing for efficient generation
  of effective policies. Importantly Gaussian processes also enable probabilistic
  constraint violation to be modelled, ensuring safe constraint satisfaction throughout
  the learning procedure. On application to the in-silico case study, a safe, effective
  policy was generated utilising only 100 evaluations of process trajectory with no
  prior knowledge of the process dynamics. A result that would require significantly
  more trajectory evaluations when compared to a neural network based approach.
publication: '*IFAC-PapersOnLine*'
doi: https://doi.org/10.1016/j.ifacol.2021.08.292
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S240589632101065X
---
