---
title: LLM-Assisted Synthesis of Strong Specifications
date: 2026-04-03
publishDate: 2026-04-02
---

**Presenter**: {{% mention "Zhongyi Wang" %}}

**Abstract**: This talk presents recent research on enhancing the strength and practical applicability of Large Language Model (LLM)-generated formal specifications for C program verification. We discuss two complementary frameworks -- AutoACSL and SpecSyn -- that address key limitations of prior LLM-based approaches, which often produce specifications lacking semantic depth, verifiability, or sufficient strength for real-world verification tasks.

AutoACSL integrates LLMs with Code Property Graph (CPG)-based static analysis to ground specification synthesis in concrete program semantics. By extracting and encoding features such as arithmetic operations, memory access patterns, and control-flow structures into structured prompts, AutoACSL guides the LLM to generate ACSL specifications that are not only behaviorally descriptive but also include constraints preventing runtime errors. Its feedback-driven synthesis loop, coupled with the Frama-C/WP verifier, achieves a 96% full proof ratio on a diverse set of 604 programs, significantly outperforming code-only baselines.

SpecSyn tackles the scalability and specification strength challenges in verifying complex, real-world programs. It decomposes large programs into manageable segments and employs an iterative synthesis process augmented with a novel refinement mechanism. This mechanism assesses and enhances the semantic strength of generated specifications using semantic-non-equivalent program mutations and variant discrimination, ensuring the synthesized contracts are both precise and robust. Evaluations show that SpecSyn maintains over 90% precision and 75% recall, and successfully handles 1071 out of 1365 target properties in open-source codebases.
