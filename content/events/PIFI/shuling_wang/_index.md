---
title: "Formal Semantics and Certified Implementation for Simulink Diagrams"
date: 2025-11-07
publishDate: 2025-10-29
---

**Speaker**: {{% mention "Shuling Wang" %}}

**Abstract**: Simulink is widely used in the design of safety-critical embedded systems, including avionics and automotive applications. In this talk, we first present a formal semantic foundation for a core subset of Simulink by defining both denotational and operational semantics. The denotational semantics offers a mathematical interpretation of the diagram’s input-output behavior, faithfully capturing its hierarchical structure. In contrast, the operational semantics specifies the concrete execution of Simulink diagrams, resolving block execution order, solving continuous dynamics, and coordinating hybrid discrete-continuous interactions. Both semantics have been fully formalized in Isabelle/HOL, and we have established their consistency by proving the existence and uniqueness of the denotational semantics. Furthermore, to facilitate application, we developed a translator that automatically converts Simulink graphical diagrams into their Isabelle representation. Our formal semantics supports the rigorous analysis of Simulink diagram properties, as demonstrated by a PID control example. In the second part of this talk, we present how to define a verified numerical semantics for Simulink diagrams, from which we get a certified implementation.
