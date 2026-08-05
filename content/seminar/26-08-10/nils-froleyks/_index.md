---
title: Certifying Symbolic Model Checking
date: 2026-08-10
publishDate: 2026-08-05
---

**Presenter**: {{% mention "Nils Froleyks" %}}

**Abstract**: Model checking complex systems is indispensable in safety-critical applications. At the same time, model checkers are becoming increasingly complex and now include components built on statistical AI, making the implementations themselves inherently difficult to trust.

This talk introduces certification for hardware model checking as a path to absolute assurance of chip-design correctness at scale. Certificates are machine-checkable proofs generated during verification and validated by an independent proof checker. Because the checker only needs to validate comparatively simple reasoning steps, small and even formally verified checker implementations are feasible.

The talk introduces our simulation-based certification approach and shows how to certify the most relevant model checking techniques in safety and liveness verification.

The research presented in this talk recently received two Distinguished Paper Awards at CAV25 and CAV26.


**Bio**: [Nils Froleyks](https://froleyks.de/) is a postdoctoral researcher at KU Leuven in Belgium, where he works with Professor Bart Bogaerts on model checking, SAT solving, and certification. He is a member of the development team for the CaDiCaL SAT solver and organizes the international Hardware Model Checking Competition.

He received Karlsruhe Institute of Technology’s Best Master’s Thesis Award in computer science for his work on symbolic planning with Professor Peter Sanders. During his PhD with Professor Armin Biere at Johannes Kepler University Linz, he authored more than 20 peer-reviewed papers. His dissertation, Deep Integration of SAT Solving and Model Checking, was a finalist for the Austrian Computer Society’s 2026 Heinz Zemanek Prize and a runner-up for the SAT Association’s 2026 Fahiem Bacchus PhD Award in Satisfiability.
