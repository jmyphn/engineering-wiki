---
layout: default
title: ECE Embedded Systems Page
permalink: /ecemajor-embedded/
---
\
\
[Home]({{ '/' | relative_url }}) → [Electrical & Computer Engineering]({{ '/ecemajor/' | relative_url }}) → Embedded Systems

# ECE Major - Embedded Systems 💻       
Field of study on the design of computing systems that integrate hardware and software for real-world application. Involves the development and unification of physical components with specialized software for use within larger electronic systems.

Career Paths: Embedded Systems Engineer, FPGA Engineer, Firmware Engineer, Systems Architect, Test Engineer

## Flow Map
```mermaid
flowchart TD
  A[Prereqs] --> F[Foundations]
  F --> S[Software/Firmware]
  F --> H[Hardware/FPGA]
  F --> R[Real-Time & Robotics]
  F --> G[Grad/Advanced Topics]

  subgraph A1[Prerequisites]
    A1a[Python/Embedded C]
    A1b[Linear Algebra]
    A1c[Calculus II/III]
    A1d[Probability/Signals]
    A1e[Circuits & Electronics]
  end

  subgraph F1[Foundations]
    F1a[ECE 2300 - Intro To Digital Logic]
    F1b[ECE 3140 - Embedded Systems]
  end

  subgraph S1[Software/Firmware]
    S1a[ECE 4760 - Digital System Design Using Microcontrollers]
    S1b[ECE 5725 - Design with Embedded Operating Systems]
  end

  subgraph H1[Hardware/FPGA]
    H1a[ECE 4740 - Intro to Digital VLSI Design]
    H1b[ECE 4750 - Computer Architecture]
  end

  subgraph R1[Real-Time & Robotics]
    R1a[ECE 5760 - Advanced Microcontroller Design]
  end

  subgraph G1[Grad/Advanced]
    G1a[ECE 5760 - Advanced Microcontroller Design]
    G1b[ECE 5725 - Design with Embedded Operating Systems]
  end

  A1a --> F1a
  A1b --> F1b
  A1c --> F1a
  A1d --> R1a
  A1e --> F1a
  F1a --> S1a
  F1a --> H1a
  F1b --> H1b
  S1a --> R1a
  H1b --> G1a
  R1a --> G1b
```

## Prerequisite Courses: 
- Programming in Python and Embedded C — for firmware, hardware interaction, and scripting toolchains.
- Linear Algebra — useful for sensor fusion, transforms, and control math.
- Calculus II/III — for continuous-time modeling and system analysis.
- Probability/Signals — for filtering, estimation, and handling sensor noise.
- Circuits  — for understanding sensors, power, and interfacing hardware.

## Core Courses:
- **ECE 2300 - Intro To Digital Logic**
  - What you'll learn: Basics of digital circuits, Boolean logic, combinational/sequential design, and simple microcontroller I/O.
  - Essential? Yes — foundational for embedded and hardware courses.
  - Recommended workflow: Take early; pair with a circuits lab and small hardware projects.
  - Prereqs and why: Intro programming and basic circuits to connect software to physical I/O.

- **ECE 3140 - Embedded Systems**
  - What you'll learn: Microcontrollers, assembly/embedded C, interrupts, I/O, concurrency, scheduling, and real-time constraints.
  - Essential? Yes — core firmware knowledge for embedded roles.
  - Recommended workflow: After ECE 2300; start hands-on projects using peripherals and debugging tools.
  - Prereqs and why: ECE 2300 (digital logic) and programming experience to implement reliable firmware.

- **ECE 4740 - Intro to Digital (VLSI) Design**
  - What you'll learn: Synchronous VLSI design, CMOS logic, layout, timing, CAD tools, and electrical/performance tradeoffs.
  - Essential? Optional — important for VLSI/ASIC career tracks.
  - Recommended workflow: Take after digital systems or ECE 3150; pair with FPGA/HDL practice.
  - Prereqs and why: Digital design background (ECE 3150 or equivalent) to understand layout and timing constraints.

- **ECE 4750 - Computer Architecture**
  - What you'll learn: Processor/memory/network building blocks, pipelining, caching, multicore design, and an RTL project workflow.
  - Essential? Recommended for architecture, FPGA, and system-level designers.
  - Recommended workflow: After ECE 3140/CS 3420; complete the RTL project sequence to gain practical RTL experience.
  - Prereqs and why: HDL familiarity and digital systems background to finish the lab sequence.

- **ECE 4760 - Digital System Design Using Microcontrollers**
  - What you'll learn: Design of microprocessor-based real-time systems through paired lab projects focused on design, debug, and integration.
  - Essential? Recommended for hands-on embedded system development.
  - Recommended workflow: Take after ECE 3140; emphasize collaborative lab work.
  - Prereqs and why: ECE 3140/CS 3420 for digital design and toolchain competence.

- **ECE 5725 - Design with Embedded Operating Systems**
  - What you'll learn: Embedded Linux, application and system programming on microcontroller platforms, hardware interfacing, and a semester project.
  - Essential? Recommended for Linux-based embedded development and system integration work.
  - Recommended workflow: After ECE 3140; build end-to-end projects on Raspberry Pi–like targets.
  - Prereqs and why: ECE 3140/CS 3420 to ensure students can handle system-level programming and hardware interfaces.

- **ECE 5760 - Advanced Microcontroller Design**
  - What you'll learn: SoC/advanced microcontroller design, custom peripherals, RTOS integration, and HW/SW co-design in labs.
  - Essential? Recommended for SoC/FPGA specialization and hardware-accelerated systems.
  - Recommended workflow: After foundational digital/embedded courses; integrate HW/SW projects.
  - Prereqs and why: Recommended ECE 5725 and prior HDL/digital experience for reliable SoC development.


