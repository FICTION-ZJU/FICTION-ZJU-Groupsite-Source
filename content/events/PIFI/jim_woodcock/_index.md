---
title: "Leadership Election in Vehicle Platoons: Pattern-Based Compositional Deadlock Verification"
date: 2025-11-07
publishDate: 2025-10-29
---

**Speaker**: {{% mention "Jim Woodcock" %}}

**Abstract**: Leadership election is a fundamental challenge for intelligent connected vehicles (ICVs) operating in platoons, where a single vehicle must coordinate speed, manoeuvres, and safety-critical decisions. Unlike traditional distributed systems, platoons feature asynchronous execution, unreliable communication, dynamic membership, and partial failures, all of which make verification especially difficult. In this talk, we present an overview of a CSP model of leadership election protocols for ICVs and describe a scalable, pattern-based verification strategy using the FDR4 model checker. Our approach guarantees deadlock freedom by design: local refinement checks of vehicles and communication entities are sufficient to ensure global correctness, even in cyclic and fault-prone topologies. We demonstrate verification of platoons with up to 64 cars, overcoming the limitations of global model checking. Beyond safety, we also address fairness in leadership roles and discuss broader implications for distributed systems and industrial applications. This work shows how formal methods can deliver verified-by-design protocols for real-world autonomous systems.
