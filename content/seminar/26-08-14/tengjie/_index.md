---
title: "Verdict: Multi-Agent Parallel Modular Verification"
date: 2026-08-14
publishDate: 2026-06-01
---

**Presenter**: {{% mention "Tengjie Lin" %}}

**Author**: Tengjie Lin, Zhongyi Wang (ZJU); Haokun Li (PKU); Jianwei Yin, Mingshuai Chen (ZJU)

**Abstract**: Deductive verification scales to large software systems through *modular reasoning*, where formal contracts summarize the behavior of individual functions and enable their independent verification. Its central bottleneck is *specification synthesis*: constructing the contracts required for modular verification. Recent advances in large language models (LLMs) have enabled automated specification synthesis at unprecedented scale. However, existing approaches remain fundamentally *bottom-up*, requiring callees to be verified before their callers. This dependency limits parallelism and provides no principled mechanism for resolving interprocedural inconsistencies that propagate across call chains.

We present Verdict, a multi-agent framework for parallelizing modular deductive verification of large-scale programs. Verdict is built on two key principles. First, *assumption-based parallel specification synthesis* assigns an agent to each function and allows it to proceed immediately using assumed contracts for its callees, enabling verification to proceed in parallel across the program. Second, *bidirectional interprocedural conflict reconciliation* resolves the inconsistencies introduced by these assumptions: when a synthesized contract contradicts an assumption, agents propagate the necessary revisions both up and down the call graph until the contracts converge. Experimental results on real-world C programs demonstrate that Verdict synthesizes higher-quality specifications than existing approaches while substantially reducing verification time. In particular, Verdict is the first approach that scales to the complete 20,000-line X.509 parser, ruling out nearly all the potential runtime errors within hours, whereas prior tools fall far short even after days of execution.
