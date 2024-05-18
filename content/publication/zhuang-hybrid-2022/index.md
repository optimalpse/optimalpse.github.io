---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A hybrid data-driven and mechanistic model soft sensor for estimating CO2 concentrations
  for a carbon capture pilot plant
subtitle: ''
summary: ''
authors:
- Yilin Zhuang
- Yixuan Liu
- Akhil Ahmed
- Zhengang Zhong
- Ehecatl A. del Rio Chanona
- Colin P. Hale
- Mehmet Mercangöz
tags:
- Carbon capture pilot plant
- Data-driven modeling
- Long short term memory
- Soft sensor
categories: []
date: '2022-12-01'
lastmod: 2024-05-18T19:36:03+01:00
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
publishDate: '2024-05-18T18:36:03.869071Z'
publication_types:
- '2'
abstract: Integrating post-combustion carbon capture and storage (CCS) facilities
  into fossil fuel power plants is considered an important step for reaching global
  carbon emission reduction targets. When the number of gas analyzers in such CCS
  units is limited, variations in the load of the power plant pose a challenge to
  determine the gaseous CO2 concentration profile in the absorber. A dynamic hybrid
  model for estimating the carbon capture absorber’s gaseous CO2 concentration profile
  has been proposed in this study. The model is built using actual process data collected
  from a carbon capture pilot plant and it combines data-driven and reaction kinetic
  (mechanistic) modeling approaches to act as a soft sensor along the absorber column.
  A subset of the process data is used for training the data-driven models and for
  estimating the parameters of the mechanistic model respectively. Dimensionality
  reduction techniques are applied to the data-driven model to reduce the input size
  and hence the size of the dynamic model elements. The outputs of the two models
  are fused by comparing the computed covariance matrices. A particular challenge
  for this work is that the collected process data has missing spatial labels and
  temporal values for the CO2 concentration measurements. The presented models are
  obtained using an encoding and interpolation approach for the missing information.
  For comparison, an alternative approach based on semi-supervised learning has been
  implemented. The performance of the resulting soft sensors is verified by using
  process data from previously unseen operating conditions. The soft sensor based
  on the proposed hybrid model outperforms the soft sensor trained by semi-supervised
  autoencoder. Overall the results indicate that the proposed approach can estimate
  the CO2 concentration percentage with an average root mean squared error of 0.123.
publication: '*Computers in Industry*'
doi: 10.1016/j.compind.2022.103747
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0166361522001440
---
