---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Discrete and mixed-variable experimental design with surrogate-based approach
subtitle: ''
summary: ''
authors:
- Mengjia Zhu
- Austin Mroz
- Lingfeng Gui
- Kim Jelfs
- Alberto Bemporad
- admin
- Ye Seol Lee
tags:
- Bayesian optimization
- Design of Experiment
- MILP
- mixed-variable
- surrogate-based optimization
categories: []
date: '2024-04-01'
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
publishDate: '2024-05-18T18:36:01.124025Z'
publication_types:
- '0'
abstract: "Experimental design plays an important role in efficiently acquiring informative\
  \ data for system characterization and deriving robust conclusions under resource\
  \ limitations. Recent advancements in high-throughput experimentation coupled with\
  \ machine learning have notably improved experimental procedures. While Bayesian\
  \ optimization (BO) has undeniably revolutionized the landscape of optimization\
  \ in experimental design, especially in the chemical domain, it's important to recognize\
  \ the role of other surrogate-based approaches within conventional chemistry optimization\
  \ problems. This is particularly relevant because many chemical problems involve\
  \ mixed-variable design space with physical constraints, making it challenging for\
  \ conventional BO approaches to obtain feasible samples during the acquisition step\
  \ while maintaining exploration capability. In this paper, we demonstrate that integrating\
  \ mixed-integer optimization strategies is one way to address these challenges effectively.\
  \ Specifically, we propose the utilization of mixed-integer surrogates and acquisition\
  \ functions--methods that offer inherent compatibility with problems with discrete\
  \ and mixed-variable design space. This work focuses on Piecewise Affine Surrogate-based\
  \ optimization (PWAS), a surrogate model capable of handling mixed-variable problems\
  \ subject to linear constraints. We demonstrate the effectiveness of this approach\
  \ in optimizing experimental planning through three case studies, each with a different\
  \ design space size and numerical complexity: i) optimization of reaction conditions\
  \ for Suzuki–Miyaura cross-coupling (fully categorical), ii) optimization of crossed-barrel\
  \ design to augment mechanical toughness (mixed-integer), and iii) solvent design\
  \ for enhanced Menschutkin reaction kinetics (mixed-integer and categorical with\
  \ linear constraints). By benchmarking PWAS against state-of-the-art optimization\
  \ algorithms, including genetic algorithms and BO variants, we offer insights into\
  \ the practical applicability of mixed-integer surrogates."
publication: '*ChemRxiv*'
doi: 10.26434/chemrxiv-2024-h37x4
links:
- name: URL
  url: https://chemrxiv.org/engage/chemrxiv/article-details/6626a713418a5379b0674df2
---
