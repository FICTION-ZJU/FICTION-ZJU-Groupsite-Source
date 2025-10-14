---
title: Compiling with Generating Functions
date: 2025-10-22
publishDate: 2025-10-14
---

**Presenter**: {{% mention "Jianlin Li" %}}

**Abstract**: We present a new approach to scaling exact inference for probabilistic programs, using generating functions (GFs) as a compilation target. Existing methods that target representations like binary decision diagrams (BDDs) achieve strong state-of-the-art results. We show that a compiler targeting GFs can be similarly competitive—and, in some cases, more scalable—on a range of inference problems where BDD-based methods perform well.
We present a formal model of this compiler, providing the first definition of GF compilation for a functional probabilistic language. We prove that this compiler is correct with respect to a denotational semantics. Our approach is implemented in a probabilistic programming system and evaluated on a range of inference problems. Our results establish GF compilation as a principled and powerful paradigm for exact inference: it offers strong scalability, good expressiveness, and a solid theoretical foundation.

**Bio**: Jianlin Li is a Ph.D. student at the University of Waterloo (since Fall 2021), co-supervised by Yizhou Zhang and Ondřej Lhoták. 
He designs probabilistic programming languages and implements compilers for sound and scalable inference. 
Previously, he worked on formal verification of adversarial robustness of deep neural networks.

**URL**: https://dl.acm.org/doi/10.1145/3747534
