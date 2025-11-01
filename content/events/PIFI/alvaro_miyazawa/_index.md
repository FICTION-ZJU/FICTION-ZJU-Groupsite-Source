---
title: "Modelling, Simulation and Verification with Diagrammatic Physical Models"
date: 2025-11-07
publishDate: 2025-10-29
---

**Speaker**: {{% mention "Alvaro Miyazawa" %}}

**Abstract**: Simulation is a favoured technique in robotics. It is, however, costly in terms of development time, and the lack of standardisation and portability of simulators limits its usability. We present RoboSim, a diagrammatic, tool-independent, domain-specific language for modelling robotic platforms and their controllers. It can be regarded as a profile of UML/SysML enriched with time primitives, differential equations, and a mathematical semantics. Our previous work on RoboSim described a notation to specify control software. In this paper, we present a novel notation to describe physical models: block diagrams that can be linked to the platform-independent software model to characterise how services required by the software are realised by actuators and sensors. Behaviours are specified by differential equations, and simulations and mathematical models of the whole system can be generated automatically. Our main contributions are a modular and extensible diagrammatic notation that supports the explicit specification of physical behaviours; a set of validation rules that identify well-formed models; a model-to-model transformation from RoboSim to an input format accepted by several simulators; and a formal semantics for mathematical reasoning.
