---
title: Data-driven Optimization for Enterprise-Wide Optimization
authors: ["damien"]
date: "2024-05-07"
image:
  preview_only: true
---

<!--more-->

<img src="trajectory_DDC_400_high_ESCAPE_r.svg" alt="A simple SVG graphic"/>

<div style="text-align: justify">
Traditionally, optimization of chemical engineering systems relies on gradients of model expressions. Depending on the effort required to develop accurate models, it might be more efficient to jump the model-building step. Instead, we can use derivative-free optimization (DFO) - also known as black-box or 'data-driven' optimization - for optimal controller tuning, reactor design, experiment design, or flowsheet design based purely on input-output evaluations. This would for example involve the use of Bayesian optimization or trust region methods to iteratively construct and optimize surrogates of the system's input-output evaluations. Rather than use black-box optimization to optimize physical systems or simulations, we can solve complex coordination problems where the black-box evaluations involve optimization problems themselves. The holy grail of process systems operations would be to integrate all decision-making units that arise in the interaction between supply chain players and their hierarchical levels of decision-making. To this end, we can use DFO to determine the coordinating 'complicating' variables in value chain and multi-level hierarchical planning-scheduling-control problems, otherwise determined by heuristics, decomposition techniques, or distributed optimization.
</div>

#### Related Publications: 

[1] D. van de Berg, T. Savage, P. Petsagkourakis, D. Zhang, N. Shah, E. A. del Rio-Chanona, 2022,"Data-driven optimization for process systems engineering applications," Chemical Engineering Science, 248, 117135. 

[2] D. van de Berg, P. Petsagkourakis, N. Shah, E. A. del Rio-Chanona, 2023a, "Data-driven coordination of subproblems in enterprise-wide optimization under organizational considerations," AIChE Journal, 69(4), e17977. 

[3] D. van de Berg, N. Shah, E. A. del Rio-Chanona, 2023b, "Hierarchical planning-scheduling-control – Optimality surrogates and derivative-free optimization," arXiv:2310.07870
