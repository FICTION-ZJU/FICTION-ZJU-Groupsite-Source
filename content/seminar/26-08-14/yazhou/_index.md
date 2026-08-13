---
title: "Formalizing the Linux eBPF Core ISA: A Mechanized Operational Semantics and Its Real-World Applications"
date: 2026-08-14
publishDate: 2026-08-13
---

**Presenter**: {{% mention "Yazhou Tang" %}}

**Author**: Shenghao Yuan, Yazhou Tang, Tianci Cao (Zhejiang University); Frédéric Besson, Jean-Pierre Talpin (INRIA); Mingshuai Chen (Zhejiang University)

**Abstract**: This paper presents a mechanized formal semantics for the Linux eBPF instruction set architecture (ISA). We develop a small-step semantics in Rocq that faithfully formalizes all 153 sequential in-kernel instructions of the eBPF ISA. The semantics is fully executable and has been validated against the official Linux eBPF test suite. This extensive testing revealed inconsistencies in our original formalization. Using this semantics, we have designed, implemented, and verified the soundness of the bit-level abstract domain employed by the Linux eBPF verifier. Our semantics also complements the existing Linux eBPF documentation by providing a rigorous formal specification. During the formalization process, we have discovered previously unknown bugs in the Linux eBPF implementation, and developed new verifier optimizations; all of these changes have been upstreamed to the latest version of the Linux kernel.

**URL**: https://2026.splashcon.org/details/oopsla-2026/75/Formalizing-the-Linux-eBPF-Core-ISA-A-Mechanized-Operational-Semantics-and-Its-Real-
