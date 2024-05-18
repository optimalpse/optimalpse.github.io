---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Investigating the Reliability and Interpretability of Machine Learning Frameworks
  for Chemical Retrosynthesis
subtitle: ''
summary: ''
authors:
- Friedrich Hastedt
- Rowan M. Bailey
- Klaus Hellgardt
- Sophia N. Yaliraki
- Ehecatl Antonio del Rio Chanona
- Dongda Zhang
tags:
- Benchmarking
- Chemical Retrosynthesis
- Graph Neural Network
- Interpretable AI
- Transformer
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
publishDate: '2024-05-18T18:36:01.557630Z'
publication_types:
- '0'
abstract: Machine learning models for chemical retrosynthesis have attracted substantial
  interest in recent years. Unaddressed challenges, particularly the absence of robust
  evaluation metrics for performance comparison, and the lack of black-box interpretability,
  obscure model limitations and impede progress in the field. We present an automated
  benchmarking pipeline designed for effective model performance comparisons. With
  an emphasis on user-friendly design, we aim to streamline accessibility and facilitate
  utilisation within the research community. Additionally, we suggest and perform
  a new interpretability study to uncover the degree of chemical understanding acquired
  by retrosynthesis models. Our results reveal that frameworks based on chemical reaction
  rules yield the most diverse, chemically valid, and feasible reactions, whereas
  purely data-driven frameworks suffer from unfeasible and invalid predictions. The
  interpretability study emphasises that incorporating reaction rules not only enhances
  model performance but also improves interpretability. For simple molecules, we demonstrate
  that Graph Neural Networks identify relevant functional groups within the product
  molecule, providing thermodynamic stabilisation over the reactant precursors. In
  contrast, the popular Transformer fails to identify such crucial stabilisation.
  As the molecule and reaction mechanism grow more complex, both data-driven models
  propose unfeasible disconnections without offering a chemical rationale. We stress
  the importance of incorporating chemically meaningful descriptors within deep-learning
  models. Our study provides valuable guidance for the future development of retrosynthesis
  frameworks.
publication: '*ChemRxiv*'
doi: 10.26434/chemrxiv-2024-qdgnv
links:
- name: URL
  url: https://chemrxiv.org/engage/chemrxiv/article-details/659ed1f066c1381729263c8a
---
