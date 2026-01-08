---
title: CompCert and its Memory Model
date: 2026-01-09
publishDate: 2026-01-08
---

**Presenter**: {{% mention "Yazhou Tang" %}}

**Author**: Xavier Leroy, Andrew W. Appel, Sandrine Blazy, Gordon Stewart

**Abstract**: CompCert is a compiler from Clight (a large subset of the C programming language) to assembly code, using the Coq proof assistant both for programming the compiler and for proving its correctness.
In this talk, I will first introduce the pipeline of CompCert and the concept of semantic preservation, which is the theoretical foundation of formal verification. Then I will focus on CompCert memory model (specification of the behavior of operations over memory states, such as reads and writes) and its evolution.

**URL**:
- Overview in 2009: https://dl.acm.org/doi/10.1145/1538788.1538814
- Memory Model (v2) in 2012: https://www.researchgate.net/publication/265570794_The_CompCert_Memory_Model_Version_2
