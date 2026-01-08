---
title: Accelerating Automated Program Verifiers by Automatic Proof Localization
date: 2026-01-09
publishDate: 2026-01-08
---

**Presenter**: {{% mention "Zhongyi Wang" %}}

**Author**: Kiran Gopinathan, Dionysios Spiliopoulos, Vikram Goyal, Peter Müller, Markus Püschel, and Ilya Sergey

**Abstract**: Automated program verifiers such as Dafny, F , Verus, and Viper are now routinely used to verify real-world software. Unfortunately, the performance of the SMT solvers employed by these tools is not always able to keep up with the increasing size and complexity of verification problems, resulting in long verification times and verification failures due to time-outs. This performance degradation occurs because large SMT queries increase the search space for the SMT solver, in particular, the number of possible quantifier instantiations. Most existing attempts to mitigate this problem require substantial manual effort to reduce the size of the search space, for instance, by decomposing proofs.
In this paper, we present an automatic technique to significantly improve the performance of SMT-based program proofs by drastically reducing the proof search space for each assertion, in particular, the performed quantifier instantiations. Starting from a successful verification, we automatically extract for each assertion the quantified axioms used by the SMT solver to show that the assertion is valid. Crucially, these include lurking axioms, which are logically irrelevant, but needed to trigger the instantiation of other, relevant axioms. We describe a novel proof localization algorithm that implements a semantics-preserving source-tosource translation of a program such that re-verifying an assertion in the optimized program uses only the axioms in its proof essence. This rewriting greatly reduces the possible quantifier instantiations and, thereby, the search space for the SMT solver, such that all future runs of the verifier, for instance as part of continuous integration, are substantially faster. We implemented our algorithm for the Boogie verifier and demonstrated its effectiveness on examples from Dafny and Viper. Specifically, for files with verification times over a minute, we show significant speedups of up to 100–1000 times and no slowdowns. We also provide some evidence that these improvements persist as projects evolve.

**URL**: https://doi.org/10.1007/978-3-031-98682-6_9
