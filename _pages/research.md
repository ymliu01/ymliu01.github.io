---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My long-term goal is to develop practical design-automation and test methods for heterogeneous integrated systems. I am especially interested in problems where package geometry, power integrity, thermal behavior, and test requirements interact.

Current Research
======

### Advanced-Package Power Delivery and Routing

I am working with a C++ planning flow for C4-bump fanout, TSV allocation, and RDL via planning. My current focus is improving the physical consistency of grid-based planning, including metal-density evaluation, current-density constraints, and scale-independent geometric analysis.

### Test Access and Scheduling for Chiplet Systems

I am exploring task and resource models for IEEE 1838-based test access architectures. The work considers serial and parallel access paths, precedence and exclusivity constraints, shared power delivery, IR drop, and transient temperature. The immediate goal is a transparent experimental framework in which every generated schedule can be checked for legality before its performance is evaluated.

Previous Work
======

### FPGA-Based DFT Platform

My undergraduate thesis implemented scan chains, BIST, fault injection, and test-control logic on an FPGA. The project helped me connect textbook DFT concepts with synthesizable RTL, simulation, and hardware demonstration.

### Automated Testing on ST3020 ATE

As a core team member, I helped build a testing workflow covering datasheet analysis, functional and parametric modeling, vector generation, automatic judgment, and coverage analysis. This project received a national second prize in the 2025 National College Student IC Innovation and Entrepreneurship Competition.

### 2.5D Power-Delivery Optimization Reproduction

I reproduced and analyzed an optimization flow for switched-capacitor voltage-regulator selection and placement in a multilayer 2.5D power-delivery network. The work involved modified nodal analysis, Schur reduction, sparse modeling, and mixed-integer linear programming.

Research Plan
======

1. **Build strong foundations.** Deepen my understanding of DFT, physical design, optimization, and production-quality C++/Python development.
2. **Develop reliable EDA methods.** Create algorithms whose assumptions, constraints, and validation procedures are explicit and reproducible.
3. **Connect test and package design.** Explore test-aware physical planning and physically aware test scheduling for chiplet systems.
4. **Validate beyond toy examples.** Use realistic benchmarks and, when feasible, prototype or silicon-oriented validation.

This page will be updated as projects mature. Results are listed only after they are ready for public release.
