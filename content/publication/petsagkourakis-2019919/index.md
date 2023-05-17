---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Reinforcement Learning for Batch-to-Batch Bioprocess Optimisation
subtitle: ''
summary: ''
authors:
- P. Petsagkourakis
- I. Orson Sandoval
- E. Bradford
- D. Zhang
- E. A. del Rio-Chanona
tags:
- Reinforcement Learning
- Batch Process
- Recurrent Neural Networks
- Bio-processes
categories: []
date: '2019-01-01'
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
publishDate: '2023-05-17T11:36:46.552617Z'
publication_types:
- '6'
abstract: Bioprocesses have received great attention from the scientific community
  as an alternative to fossil-based products by microorganisms-synthesised counterparts.
  However, bioprocesses are generally operated at unsteady-state conditions and are
  stochastic from a macro-scale perspective, making their optimisation a challenging
  task. Furthermore, as biological systems are highly complex, plant-model mismatch
  is usually present. To address the aforementioned challenges, in this work, we propose
  a reinforcement learning based online optimisation strategy. We first use reinforcement
  learning to learn an optimal policy given a preliminary process model. This means
  that we compute diverse trajectories and feed them into a recurrent neural network,
  resulting in a policy network which takes the states as input and gives the next
  optimal control action as output. Through this procedure, we are able to capture
  the previously believed behaviour of the biosystem. Subsequently, we adopted this
  network as an initial policy for the “real” system (the plant) and apply a batch-to-batch
  reinforcement learning strategy to update the network’s accuracy. This is computed
  by using a more complex process model (representing the real plant) embedded with
  adequate stochasticity to account for the perturbations in a real dynamic bioprocess.
  We demonstrate the effectiveness and advantages of the proposed approach in a case
  study by computing the optimal policy in a realistic number of batch runs.
publication: '*29th European Symposium on Computer Aided Process Engineering*'
doi: https://doi.org/10.1016/B978-0-12-818634-3.50154-5
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/B9780128186343501545
---
