---
title: Tristate Numbers Abstract Domain in eBPF Verifier
date: 2025-06-27
publishDate: 2025-06-25
---

**Presenter**: {{% mention "Yazhou Tang" %}}

**Author**: Harishankar Vishwanathan, Matan Shachnai, Srinivas Narayana, and Santosh Nagarakatte

**Abstract**: Extended Berkeley Packet Filter (BPF) is a language and run-time system that allows non-superusers to extend the Linux and Windows operating systems by downloading user code into the kernel. To ensure that user code is safe to run in kernel context, BPF relies on a static analyzer that proves properties about the code, such as bounded memory access and the absence of operations that crash. The BPF static analyzer checks safety using abstract interpretation with several abstract domains. Among these, the domain of tnums (tristate numbers) is a key domain used to reason about the bitwise uncertainty in program values.

This paper formally defines the tnum abstract domain and its arithmetic operations. They present the first soundness and optimality proofs for tnum addition/subtraction in BPF analyzers. They also propose a novel, more precise and efficient tnum multiplication algorithm than Linux's, which is now merged into the kernel.

Moreover, I will talk briefly about the tnum+ abstract domain presented in another paper, which is a generalization and extension of the tnum abstract domain, and the combination domain based on it. Finally, I will introduce our current work on formal verification of tnum theory.

**URL**:
* CGO'22: https://people.cs.rutgers.edu/~sn349/papers/cgo-2022.pdf
* ISSTA'25: https://rainoftime.github.io/files/ISSTA25.pdf
