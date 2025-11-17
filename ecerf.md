---
layout: default
title: ECE Analog and RF Circuit Page
permalink: /ecemajor-analog-rf/
---
\
\
[Home]({{ '/' | relative_url }}) → [Electrical & Computer Engineering]({{ '/ecemajor/' | relative_url }}) → Analog and RF Circuit Design
# ECE Major - Analog and RF Circuit Design ⚡        
Field of study focused on the design and innovation of electronic systems and integrated circuits for efficiency and functionality in modern technology.

## Flow Map
```mermaid
flowchart TD
  A[Prereqs] --> F[Foundations]
  F --> R[Analog / RF]
  F --> P[Power Electronics]
  F --> N[Nanofab & Characterization]

  subgraph A1[Prerequisites]
    A1a[Circuits - ECE 2100]
    A1b[Physics - PHYS 2213]
    A1c[Linear Algebra / Calculus]
    A1d[Intro Electronics prep]
  end

  subgraph F1[Foundations]
    F1a[ECE 3150 - Microelectronics]
  end

  subgraph R1[Analog/RF]
    R1a[ECE 4330 - Microwave Circuit Design]
    R1b[ECE 4530 - Analog IC Design]
  end

  subgraph P1[Power]
    P1a[ECE 4560 - Power Electronics]
  end

  subgraph N1[Nanofab]
    N1a[ECE 4360 - Nanofabrication]
    N1b[ECE 4361 - Nanofabrication Lab]
  end

  A1a --> F1a
  A1b --> F1a
  A1c --> F1a
  F1a --> R1a
  F1a --> R1b
  F1a --> P1a
  F1a --> N1a
  N1a --> N1b
```

## Prerequisite Courses:
- **Circuits (ECE 2100/ENGRD 2100)** — basic circuit analysis used everywhere in analog/RF/power work.
- **Physics (PHYS 2213)** — semiconductor/solid-state fundamentals for device-level understanding.
- **Calculus & Linear Algebra** — continuous modeling, small-signal analysis, and matrix methods in circuits.
- **Intro electronics / prior device exposure** — helps when starting ECE 3150 and higher-level IC or RF design.

## Core Courses:
- **ECE 3150 - Microelectronics**
  - What you'll learn: Semiconductor physics, PN junctions, MOS/BJT device models, small‑signal analysis, single/multi‑stage amplifiers, high‑frequency models, CMOS logic, and lab/project work.
  - Essential? Yes — the primary foundation for analog, RF, and power-electronics topics.
  - Recommended workflow: Take early after circuits and physics; use labs to build device intuition.
  - Prereqs and why: ECE 2100/PHYS 2213 to understand device operation and circuit-level implications.

- **ECE 4330 - Microwave Circuit Design**
  - What you'll learn: Planar transmission lines, network analysis, S‑parameters, matching networks, resonators, filters, power dividers, and microwave measurement/simulation workflows.
  - Essential? Recommended for RF/mm‑wave and high‑frequency design specializations.
  - Recommended workflow: After ECE 3150 and E&M fundamentals; pair with hands‑on measurement or EM simulation projects.
  - Prereqs and why: ECE 3030 (electromagnetics) and ECE 3150 to connect device/circuit behavior with wave/line phenomena.

- **ECE 4360 - Nanofabrication and Characterization of Electronics**
  - What you'll learn: Nanofabrication processes (lithography, metallization, etching, annealing), device fabrication steps, process modeling, and integration considerations for IC manufacturing.
  - Essential? Optional — important if you plan to work on fabrication, device research, or integration challenges.
  - Recommended workflow: After ECE 3150; take the paired lab (ECE 4361) to get hands‑on fabrication experience.
  - Prereqs and why: MSE 2620 or ECE 3150 and supporting math/chemistry to understand process physics and device behavior.

- **ECE 4361 - Nanofabrication and Characterization Lab**
  - What you'll learn: Hands‑on fabrication and characterization of devices (diodes, MOS capacitors, MOSFETs, 2D/GaN devices), cleanroom workflows, and measurement techniques.
  - Essential? Recommended if pursuing device/process work; complements ECE 4360.
  - Recommended workflow: Take alongside or after ECE 4360; focus on lab safety and process sequence mastery.
  - Prereqs and why: Core fabrication lecture background (ECE 4360 or equivalent) to meaningfully perform and interpret lab work.

- **ECE 4530 - Analog Integrated Circuit Design**
  - What you'll learn: Transistor‑level design for linear analog ICs — single‑stage amplifiers, current mirrors, differential pairs, op‑amp design, and layout techniques for analog circuits.
  - Essential? Yes for students targeting analog IC design roles.
  - Recommended workflow: After ECE 3150; perform transistor‑level design labs and layout assignments.
  - Prereqs and why: ECE 3150 provides device models and small‑signal tools used in IC design.

- **ECE 4560 - Power Electronics**
  - What you'll learn: Modeling and design of power converters, semiconductor device modeling for power switches, thermal/magnetic/component modeling, EMI filtering, and switching converter control.
  - Essential? Recommended for students interested in power conversion and energy systems.
  - Recommended workflow: After ECE 3150 and circuits; pair with lab or project work on converters and control.
  - Prereqs and why: ECE 3150 or instructor permission to ensure familiarity with device behavior and non‑linear converter analysis.

## Relevant / Additional Notes:
- Use ECE 3150 as the central foundation and pick downstream courses depending on specialization: RF (4330, 4530), Power (4560), or Fabrication (4360/4361).