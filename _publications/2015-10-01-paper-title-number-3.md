---
title: "Rigorous benchmarking of an iterative IBM solver by comparison to body-fitted mesh results"
collection: publications
category: manuscripts
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'This study addresses the validation challenges of Immersed Boundary Method (IBM) solvers by proposing a consistent benchmarking approach. A temporally second-order Arbitrary Lagrangian–Eulerian (ALE) solver implemented in OpenFOAM is verified against lid-driven cavity flow and flow past static and oscillating cylinders. It then serves as the underlying fluid flow solver for a fully implicit diffusive direct forcing IBM solver that achieves temporal second-order accuracy, verified by the static and oscillating cylinder cases. Leveraging the shared numerical framework, the IBM solver is rigorously validated against ALE using identical settings, parameters, and nearly identical grids across twenty test cases, including stationary cylinder flow (Re = 40, 100, 185), oscillating cylinder in quiescent flow (Re = 100, KC = 5), and transversely oscillating cylinders with varying amplitudes and frequencies (16 cases in total). The IBM solver demonstrates robustness (CFL up to 8) and accuracy over a wide Reynolds number range, with relative drag coefficient errors below 7% for all considered cases. Incorporating body force correction, which reduces slip errors at negligible added computational cost, drastically improves accuracy. Proper Rhie–Chow momentum interpolation, including body forces, is critical in the adopted collocated finite volume method. For unsteady problems, the computational cost is greatly reduced without compromising accuracy by using CFL=1.5-2.0 with only two outer iterations. The proposed benchmarking framework can be easily used for validation of other IBM approaches and thus potentially help to advance the state of IBM.'
date: 2024-04-26
venue: 'Computers & Fluids'
slidesurl: 'http://lianxiali.github.io/files/slides3.pdf'
paperurl: 'http://lianxiali.github.io/files/paper3.pdf'
citation: 'L. Li, M. Stoellinger, and M. Mousaviraad, &quot Rigorous benchmarking of an iterative IBM solver by comparison to body-fitted mesh results. &quot <i> Computers & Fluids </i>, vol. 277, p. 106 281, 2024. '
---

