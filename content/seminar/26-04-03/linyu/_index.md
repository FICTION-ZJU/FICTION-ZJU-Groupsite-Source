---
title: Lemma Syntheses in Lean4 with Large Language Models
date: 2026-04-03
publishDate: 2026-04-02
---

**Presenter**: {{% mention "Linyu Yang" %}}

**Abstract**: This talk presents recent progress in integrating classical techniques with large language models for lemma synthesis in interactive theorem proving, particularly in the context of equivalence proofs for functional programs. On the classical side, we primarily rely on the exhaustive proof search tool `Canonical`, together with traditional SMT solvers, to ensure the soundness of proof checking. However, these techniques are limited in forward reasoning, especially in generating and applying useful lemmas. To address this limitation, we leverage large language models for heuristic lemma generation. Finally, we outline the remaining challenges and discuss several possible directions for addressing them.

**URL**:
- Canonical:
  - https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.ITP.2025.14
  - https://github.com/chasenorman/CanonicalLean
- lean-auto: https://github.com/leanprover-community/lean-auto
- AutoProof: https://link.springer.com/chapter/10.1007/978-3-031-71162-6_28
