---
permalink: /markdown/
title: "Computational codes"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---
## DMS-Reduction

## LOG-DMS

## LOG-DS

## DMS-FILTER-IR
The DMS-FILTER-IR algorithm is an innovative approach to multiobjective derivative-free optimization with general constraints, combining a filter strategy and inexact restoration techniques. Unlike traditional methods that rely on an extreme barrier approach, DMS-FILTER-IR evaluates feasible and infeasible points, treating constraint violations as an additional objective to minimize. By prioritizing feasibility improvement through an inexact restoration step, the algorithm ensures efficient exploration of the solution space. Operating within the Direct Multisearch (DMS) framework, it dynamically updates a list of nondominated points, balancing feasibility and optimality. This method is particularly suited for complex optimization problems lacking gradient information, offering theoretical convergence guarantees to Pareto-Clarke critical points and demonstrating competitive performance in numerical experiments.
[DMS-FILTER-IR](https://github.com/EvertonJdaSilva/DMS-FILTER-IR)


## Mean Value and Level Set (MVLSM)
The MVLSM Algorithm is a numerical approach developed to approximate the weak Pareto front in multiobjective optimization problems (MOPs). Building on integral global optimality conditions, the MVLSM algorithm employs scalarization techniques, particularly weighted sum and Chebyshev scalarizations, to convert multiobjective problems into single-objective optimization problems. This method enables the identification of weak Pareto optimal solutions by solving classical nonlinear programming problems. The algorithm is inspired by an integration-based optimality characterization for non-differentiable multiobjective problems, which relies on the continuity of the objective function and the compactness of the feasible set. By extending earlier work in single-objective optimization, the MVLSM algorithm effectively approximates the weak Pareto front using integration techniques that account for the mean value and variance on the level sets of the objective function. Numerical experiments demonstrate the algorithm's effectiveness in solving multiobjective test problems, making it an efficient tool for global optimization in non-smooth, non-convex contexts.
