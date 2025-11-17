---
layout: default
title: Low-Level Systems Page
permalink: /csmajor-comparch/
---
\
\
[Home]({{ '/' | relative_url }}) → [Computer Science]({{ '/csmajor/' | relative_url }}) → Low-Level Systems

# CS Major - Low-Level Systems ⚙️      
Field of study on the design and construction of computer systems and their component parts.

## Flow Map
```mermaid
flowchart TD
  subgraph A1[Prerequisites]
    A1a[C/C++/Rust]
    A1b[Data Structures]
    A1c[Discrete Math/Logic]
  end

  subgraph B1[Foundations]
    B1a[ECE 2300 Digital Logic]
  end

  subgraph C1[Architecture]
    C1a[CS 4420 Computer Architecture]
  end

  subgraph D1[Advanced Arch]
    D1a[CS 5420 Advanced Computer Architecture]
  end

  subgraph E1[Systems]
    E1a[CS 4414 Systems Programming]
  end

  subgraph F1[OS]
    F1a[CS 4410/4411 Operating Systems]
  end

  subgraph G1[Embedded]
    G1a[CS 3420 Embedded Systems]
    G1b[ECE 5725 Design with Embedded OS]
  end

  subgraph H1[PL & Compilers]
    H1a[CS 4120/4121 Compilers]
  end

  subgraph I1[Advanced PL]
    I1a[CS 6120 Advanced Compilers]
  end

  subgraph J1[HPC]
    J1a[CS 5220 High-Performance & Parallel]
  end

  subgraph K1[Parallel]
    K1a[CS 6230 Parallel Arch, Algorithms & Apps]
  end

  A1a --> E1a
  A1b --> H1a
  A1c --> B1a
  B1a --> C1a
  C1a --> D1a
  E1a --> F1a
  F1a --> G1a
  F1a --> J1a
  H1a --> I1a
  J1a --> K1a
```

## Prerequisite Courses:
- Programming in C/C++ (and/or Rust) — systems-level coding, memory models, tooling
- Data Structures & Algorithms (e.g., CS 2110/2112) — performance, correctness of core components
- Discrete Math & Logic (e.g., CS 2800) — FSMs, invariants, correctness proofs
- Computer Organization basics (e.g., ECE 2300) — ISA, pipelines, memory hierarchy
- Calculus & Probability — performance modeling, queuing, cache behavior probabilities
- Operating system concepts (intro exposure) — processes, memory, filesystems context

## Core Courses:
- **ECE 2300 - Digital Logic and Computer Organization**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Boolean logic, combinational/sequential circuits, datapaths, and basic CPU organization.</li>
    <li>- Essential? Yes for hardware/architecture; helpful context for systems.</li>
    <li>- Recommended workflow: Take early; pair with a simple CPU design or FPGA lab if available.</li>
    <li>- Prereqs and why: Discrete math/logic (for circuit reasoning); basic programming.</li>
    </ul>
  </details>

- **CS 3420 - Embedded Systems**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Microcontrollers, interrupts, real-time constraints, I/O, and bare-metal C.</li>
    <li>- Essential? Recommended for embedded/firmware tracks.</li>
    <li>- Recommended workflow: After or alongside OS/systems programming; do hands-on labs.</li>
    <li>- Prereqs and why: C programming (for low-level), basic electronics (for hardware interfaces).</li>
    </ul>
  </details>

- **CS 4120 - Intro to Compilers**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Lexing, parsing, static analysis, IR, optimization, code generation.</li>
    <li>- Essential? Core for PL/compilers; valuable for general systems understanding.</li>
    <li>- Recommended workflow: After data structures and architecture; do the course project seriously.</li>
    <li>- Prereqs and why: Discrete math/automata (parsing), data structures (IR/opt), architecture (codegen).</li>
    </ul>
  </details>

- **CS 4121 - Intro to Compilers Practicum**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Implementation-heavy companion to 4120; end-to-end compiler components.</li>
    <li>- Essential? Recommended if you want deeper hands-on skills.</li>
    <li>- Recommended workflow: Take with or right after 4120; split work across milestones.</li>
    <li>- Prereqs and why: Same as 4120; strong programming discipline for larger codebases.</li>
    </ul>
  </details>

- **CS 4410 - Operating Systems**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Processes/threads, scheduling, memory management, filesystems, virtualization.</li>
    <li>- Essential? Yes for nearly all systems roles.</li>
    <li>- Recommended workflow: After systems programming; prioritize the programming labs.</li>
    <li>- Prereqs and why: C, concurrency primitives, and computer architecture (for memory/CPU models).</li>
    </ul>
  </details>

- **CS 4411 - Operating Systems Practicum**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Hands-on labs building OS components (threading, VM, FS, networking).</li>
    <li>- Essential? Highly recommended to solidify OS concepts.</li>
    <li>- Recommended workflow: Co-enroll with 4410; start labs early.</li>
    <li>- Prereqs and why: C programming and debugging (gdb), 4410 concepts.</li>
    </ul>
  </details>

- **CS 4414 - Systems Programming**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Low-level programming (often Rust/C), concurrency, networking, and tooling.</li>
    <li>- Essential? Recommended prep for OS/networking/distributed systems.</li>
    <li>- Recommended workflow: Before 4410/4450; build robust, tested system components.</li>
    <li>- Prereqs and why: Data structures, comfort with pointers/memory safety.</li>
    </ul>
  </details>

- **CS 4420  - Computer Architecture**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Pipelines, caches, memory hierarchies, ILP/TLP, and performance modeling.</li>
    <li>- Essential? Yes for architecture/performance roles; beneficial context for all systems.</li>
    <li>- Recommended workflow: After digital logic; pair with performance profiling exercises.</li>
    <li>- Prereqs and why: Digital logic (for microarchitecture), probability (for performance models) helpful.</li>
    </ul>
  </details>

- **CS 5220 - High-Performance and Parallel Computing**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Parallel programming models (OpenMP/MPI/CUDA), cache-aware algorithms, performance.</li>
    <li>- Essential? Recommended for performance/HPC or large-scale systems work.</li>
    <li>- Recommended workflow: After OS/architecture; profile and tune on real workloads.</li>
    <li>- Prereqs and why: C/C++ (low-level control), OS/architecture (for memory/caches), linear algebra (for numeric workloads) helpful.</li>
    </ul>
  </details>

- **CS 5420  - Advanced Computer Architecture**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Advanced microarchitecture, coherence, interconnects, accelerators, and research trends.</li>
    <li>- Essential? Advanced elective for architecture/perf specialists.</li>
    <li>- Recommended workflow: After 4420; consider a research or simulator project.</li>
    <li>- Prereqs and why: Strong architecture background; probability/perf analysis skills.</li>
    </ul>
  </details>

- **ECE 5725 - Design with Embedded Operating Systems**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Linux on embedded, device drivers, real-time constraints, and peripherals.</li>
    <li>- Essential? Recommended for embedded/IoT; bridges OS concepts with hardware.</li>
    <li>- Recommended workflow: After embedded systems and OS; build an end-to-end device project.</li>
    <li>- Prereqs and why: C/C++, OS, and hardware I/O basics (SPI/I2C/UART).</li>
    </ul>
  </details>

- **CS 6120 - Advanced Compilers**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Modern compiler optimizations, SSA, JITs, analysis frameworks, and research papers.</li>
    <li>- Essential? Advanced elective for PL/compilers/perf engineering.</li>
    <li>- Recommended workflow: After 4120/4121; pursue an optimization-focused project.</li>
    <li>- Prereqs and why: 4120/4121, strong algorithms background, and architecture for codegen/perf.</li>
    </ul>
  </details>

- **CS 6230 - Parallel Architectures, Algorithms, and Applications**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Parallel machines, algorithm design for parallelism, synchronization, and scaling.</li>
    <li>- Essential? Advanced elective for HPC/distributed/perf.</li>
    <li>- Recommended workflow: After 5220 or equivalent; measure and analyze scaling behavior.</li>
    <li>- Prereqs and why: Algorithms, architecture, and parallel programming experience.</li>
    </ul>
  </details>
