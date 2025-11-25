---
permalink: /markdown/
title: "Computational codes"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---
## LOG-DMS

## DMS-Reduction
Based on reduction approaches, employing correlation or sketching techniques, we propose a new variant of DMS, namely DMS-Reduction.
This reduction method aims to tackle large problems by decreasing both the number of objective function components and the number of problem variables. Reducing the number of components of the objective function to be optimized at each iteration, has the additional benefit of potentially conducting to a reduction in the number of variables to be optimized, since there could be the case that not all variables are related to the objective function components selected. We detail the proposed algorithm and report a large set of numerical experiments that demonstrate the potential of this approach in addressing many-objective optimization problems.

## LOG-DS

## DMS-FILTER-IR
The DMS-FILTER-IR algorithm is an innovative approach to multiobjective derivative-free optimization with general constraints, combining a filter strategy and inexact restoration techniques. Unlike traditional methods that rely on an extreme barrier approach, DMS-FILTER-IR evaluates feasible and infeasible points, treating constraint violations as an additional objective to minimize. By prioritizing feasibility improvement through an inexact restoration step, the algorithm ensures efficient exploration of the solution space. Operating within the Direct Multisearch (DMS) framework, it dynamically updates a list of nondominated points, balancing feasibility and optimality. This method is particularly suited for complex optimization problems lacking gradient information, offering theoretical convergence guarantees to Pareto-Clarke critical points and demonstrating competitive performance in numerical experiments.
[DMS-FILTER-IR](https://github.com/EvertonJdaSilva/DMS-FILTER-IR)


## Mean Value and Level Set (MVLSM)
The MVLSM Algorithm is a numerical approach developed to approximate the weak Pareto front in multiobjective optimization problems (MOPs). Building on integral global optimality conditions, the MVLSM algorithm employs scalarization techniques, particularly weighted sum and Chebyshev scalarizations, to convert multiobjective problems into single-objective optimization problems. This method enables the identification of weak Pareto optimal solutions by solving classical nonlinear programming problems. The algorithm is inspired by an integration-based optimality characterization for non-differentiable multiobjective problems, which relies on the continuity of the objective function and the compactness of the feasible set. By extending earlier work in single-objective optimization, the MVLSM algorithm effectively approximates the weak Pareto front using integration techniques that account for the mean value and variance on the level sets of the objective function. Numerical experiments demonstrate the algorithm's effectiveness in solving multiobjective test problems, making it an efficient tool for global optimization in non-smooth, non-convex contexts.
