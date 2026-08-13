---
title: LLM-Assisted Synthesis of High-Assurance C Programs
date: 2026-08-14
publishDate: 2025-09-01
---

**Presenter**: {{% mention "Xiaqing Zhou" %}}

**Author**: Prasita Mukherjee, Minghai Lu, Benjamin Delaware

**Abstract**: We present SYNVER — a novel, general purpose synthesizer for C programs equipped with machine-checked proofs of correctness using the Verified Software Toolchain. To do so, SYNVER employs two Large Language Models (LLMs): the first generates candidate programs from user-provided specifications, and the second helps automatically construct formal proofs of their correctness in the Rocq proof assistant. To facilitate verification, SYNVER places a set of syntactic restrictions on candidate programs that make them amenable to automated reasoning. SYNVER uses a hybrid verification strategy that combines symbolic reasoning with LLM-powered proof generation to discharge proof obligations that the symbolic engine cannot handle on its own. We demonstrate the applicability of SYNVER using a diverse set of benchmarks drawn from the program synthesis and verification literature.

**URL**: https://dl.acm.org/doi/pdf/10.1109/ASE63991.2025.00255
