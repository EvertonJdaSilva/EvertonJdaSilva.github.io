---
title: "An Inexact Restoration Direct Multisearch Filter Approach to Constrained Optimization"
collection: talks
type: "Seminars in Universities and Research Centers"
permalink: /talks/SAPIENZA2023
slidesurl: 'http://academicpages.github.io/files/SAPIENZA_Slides.pdf'
venue: "Department of Computer, Control and Management Engineering of Sapienza University of Rome"
date: 2023-12-13
location: "Rome, Italy"
---

## An Inexact Restoration Direct Multisearch Filter Approach to Constrained Optimization

[More information here](https://www.diag.uniroma1.it/en/node/27559)

Direct Multisearch (DMS) is a class of methods for multiobjective derivative-free optimization that has a well-established convergence analysis and competitive computational implementations, being often used as benchmark for new algorithms or in practical applications. From a theoretical point of view, DMS was developed for continuous optimization with general constraints, using an extreme barrier approach where only feasible points are evaluated. In this work, we propose the integration of an inexact restoration filter approach in DMS, to address optimization problems with general constraints. Like in any filter approach, violations of the relaxable constraints are addressed as an additional objective that needs to be minimized. The inexact restoration approach attempts to recover feasibility when the poll center is infeasible. Under mild assumptions, we prove that the so-called DMS-FILTER-IR algorithm generates feasible and/or infeasible subsequences of iterates that converge to either a Pareto stationary point, in the feasible case, or to a Pareto stationary point for the problem that only considers the unrelaxable constraints, potentially serving as a Pareto stationary point of the original problem, in the infeasible case. We will detail the proposed algorithm, provide theoretical results on convergence, and report numerical experiments that state the good performance of this approach to address multiobjective problems with general constraints.

Joint work with Ana L. Custódio

Acknowledgments: This research was financially supported by Fundação para a Ciência e a Tecnologia (FCT) (Portuguese Foundation for Science and Technology) through projects UIDB/00297/2020, UIDP/00297/2020, and UI/BD/151246/2021 (Centro de Matemática e Aplicações - NOVA Math).