---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Expert-guided Bayesian Optimisation for Human-in-the-loop Experimental Design
  of Known Systems
subtitle: ''
summary: ''
authors:
- tom
- admin
tags: []
categories: []
date: '2023-12-01'
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
publishDate: '2024-05-18T18:36:01.770841Z'
publication_types:
- '1'
abstract: Domain experts often possess valuable physical insights that are overlooked
  in fully automated decision-making processes such as Bayesian optimisation. In this
  article we apply high-throughput (batch) Bayesian optimisation alongside anthropological
  decision theory to enable domain experts to influence the selection of optimal experiments.
  Our methodology exploits the hypothesis that humans are better at making discrete
  choices than continuous ones and enables experts to influence critical early decisions.
  At each iteration we solve an augmented multi-objective optimisation problem across
  a number of alternate solutions, maximising both the sum of their utility function
  values and the determinant of their covariance matrix, equivalent to their total
  variability. By taking the solution at the knee point of the Pareto front, we return
  a set of alternate solutions at each iteration that have both high utility values
  and are reasonably distinct, from which the expert selects one for evaluation. We
  demonstrate that even in the case of an uninformed practitioner, our algorithm recovers
  the regret of standard Bayesian optimisation.
publication: ''
links:
- name: URL
  url: https://openreview.net/forum?id=hrFfR1WZgi
---
