---
title: Data-Driven Optimization
authors: ["mathias"]
date: "2024-05-07"
image:
  focal_point: 'top'
---

<!--more-->

<div style="text-align: justify">
Many engineering optimization problems can be described as "costly" black box problems, where the number of function evaluations is constrained. Engineers often create precise models of physical systems that are either differentiable or inexpensive to evaluate. These models can be solved efficiently, and their solutions can be applied to the actual system. However, when gradient information or cost-effective models are not available, it becomes necessary to use efficient optimization methods that rely solely on function evaluations - "data". These data-driven optimization algorithms are tailored to optimize functions without relying on explicit derivative information. The methods generally fall into two primary categories: model-based derivative-free methods, also referred to as surrogate-based optimization, and direct derivative-free methods. Model-based methods use information obtained through sampling the objective function to build, consult and update a model of the objective function during optimization. Direct methods navigate the optimization process based on sampled information only. Situated in-between these two categories are the finite-difference methods, which approximate derivatives using function evaluations.
</div>