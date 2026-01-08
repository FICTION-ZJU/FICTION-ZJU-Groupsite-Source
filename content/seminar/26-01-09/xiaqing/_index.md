---
title: "Atmosphere: Practical Verified Kernels with Rust and Verus"
date: 2026-01-09
publishDate: 2026-01-08
---

**Presenter**: {{% mention "Xiaqing Zhou" %}}

**Author**: Xiangdong Chen, Zhaofeng Li, Jerry Zhang (University of Utah); Vikram Narayanan (Palo Alto Networks); Anton Burtsev (University of Utah)

**Abstract**: Recent advances in programming languages and automated formal reasoning have changed the balance between the complexity and practicality of developing formally verified systems. Our work leverages Verus, a new verifier for Rust that combines ideas of linear types, permissioned reasoning, and automated verification based on satisfiability modulo theories (SMT), for the development of a formally verified microkernel, Atmosphere.
Atmosphere is a full-featured microkernel with support for strict isolation in mixed-criticality systems. We develop all code in Rust and prove its functional correctness, i.e., refinement of a high-level specification, with Verus. Development and verification of 6K lines of executable code required an effort of less than 2.5 person-years (only 1.5 years were spent on verification, another person-year was spent developing non-verified parts of the system). On average, our code has a proof-to-code ratio of 3.32:1 and completes verification in less than 20 seconds on a modern laptop, which we argue is practical for the development of verified systems.

**URL**: https://dl.acm.org/doi/10.1145/3731569.3764821
