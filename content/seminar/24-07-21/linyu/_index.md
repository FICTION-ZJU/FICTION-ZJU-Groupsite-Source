---
title: Automated Verification of Higher-Order Probabilistic Programs via a Dependent Refinement Type System
date: 2024-07-21
---

**Presenter**: {{% mention "Linyu Yang" %}}

**Authors**: Satoshi Kura and Hiroshi Unno

**Abstract**: Verification of higher-order probabilistic programs is a challenging problem. We present a verification method that supports several quantitative properties of higher-order probabilistic programs. Usually, extending verification methods to handle the quantitative aspects of probabilistic programs often entails extensive modifications to existing tools, reducing compatibility with advanced techniques developed for qualitative verification. In contrast, our approach necessitates only small amounts of modification, facilitating the reuse of existing techniques and implementations. On the theoretical side, we propose a dependent refinement type system for a generalised higher-order fixed point logic (HFL). Combined with continuation-passing style encodings of properties into HFL, our dependent refinement type system enables reasoning about several quantitative properties, including weakest pre-expectations, expected costs, moments of cost, and conditional weakest pre-expectations for higher-order probabilistic programs with continuous distributions and conditioning. The soundness of our approach is proved in a general setting using a framework of categorical semantics so that we don’t have to repeat similar proofs for each individual problem. On the empirical side, we implement a type checker for our dependent refinement type system that reduces the problem of type checking to constraint solving. We introduce admissible predicate variables and integrable predicate variables to constrained Horn clauses (CHC) so that we can soundly reason about the least fixed points and samplings from probability distributions. Our implementation demonstrates that existing CHC solvers developed for non-probabilistic programs can be extended to a solver for the extended CHC with only small efforts. We also demonstrate the ability of our type checker to verify various concrete examples.

**URL**: https://dl.acm.org/doi/10.1145/3674662
