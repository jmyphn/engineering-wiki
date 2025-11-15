---
layout: default
title: ECE Power Systems Page
permalink: /ecemajor-powersystems/
---
\
\
[Home]({{ '/' | relative_url }}) → [Electrical & Computer Engineering]({{ '/ecemajor/' | relative_url }}) → Power Systems
# ECE Major - Power Systems 🔌        
Field of study on the generation, transmission, distribution, and control of electrical power. Involves designing, analyzing, and maintaining function of power systems.

Career Paths: Power Systems Engineer, Transmission Line Design Engineer, Field Service Engineer, Power Electronics Engineer, Controls Engineer

## Flow Map
```mermaid
flowchart TD
    A[Prereqs]
    A --> G[Microelectronics]
    G --> H[Power Electronics]
    A --> E[Optimization]
    A --> C[Introduction Power Systems]
    A --> I[Energy Systems]
    C --> D[Advanced Power Systems]
    A --> F[Further Industry Discussion]

    subgraph A1[Prereqs]
        A1a[Python/Matlab]
        A1b[Linear Algebra]
        A1c[Calculus I, II, III]
        A1e[Thermodynamics]
        A1f[Probability]
        A1g [Signals& Systems]
        A1h[Circuits]

    end

    subgraph C1[Introduction Power Systems]
        C1a[ECE 4510 - Power Systems I]
        

    end

    subgraph D1[Advanced Power Systems]
        D1a[ECE 4520 - Power Systems II]

    end

    subgraph E1[Optimization]
        E1a[ECE 4800 - Optimal Systems Analysis]
        
    end
    
    subgraph G1[Microelectronics]
        G1a[ECE 3150 - Microelectronics]
        
    end

    subgraph H1[Power Electronics]
        H1a[ECE 4560 - Power Electronics]
        
    end

    subgraph I1[Energy Systems]
        I1a[MAE 5010 - Future Energy Systems]
        
    end
    subgraph F1[Further Industry Discussion]
        F1a[ECE 5870 - Energy Seminar I]
        F1b[ECE 5880 - Energy Seminar II]
        
    end

    C1a --> D1a
    G1a --> H1a
    A1e --> I1a
    D1a -->F1a
    F1a --> F1b
    I1a --> F1a
    A1g --> D1a
    A1b --> E1a
    A1c --> E1a
    A1h --> G1a
    A1a --> C1a
    A1a --> E1a

## Core Courses:   
- **ECE 4800 - Optimal Systems Analysis**
    Introduction to optimization theory and algorithms for system analysis and design. Topics include linear programming, convex programming, duality. We may touch dynamic programming around the end if time permits. Application will be discussed in various areas including geometric problems, networks, control, circuits, signal processing, and communications.

- **ECE 4510 - Power Systems I**
    Acquaints students with modern electric power system modeling, analysis and computation. Stresses analysis techniques appropriate for power system modeling, analysis and power flow computation. Topics include transmission line models, transformers and per unit system, generator models, network matrices, power flow analysis and computation, real and reactive power control, voltage control, economic dispatch

- **ECE 4560 - Power Electronics**
    The course will also introduce seniors and first-year graduate students to other advanced topics which are required for the analysis and design of power converters, including power semiconductor device modeling, thermal modeling, magnetic component modeling, electromagnetic interference (EMI) filter design, and switching converter control design, at a level appropriate for them. This course will equip ECE students with the theoretical and practical skills needed to innovate in the area of power electronics, and allow them to succeed in graduate school and in the rapidly growing job market for power electronic engineers.

- **ECE 4520 - Power Systems II**
    Examines the operations of electric power systems, the smart grid, and electricity markets. Topics include modeling of power systems, power flow analysis, economic dispatch, optimal power flow, unit commitments, electricity markets, demand response, smart grid technology, and transactive energy.

- **ECE 5870 - Energy Seminar I**
    Energy Seminars will explore energy-related topics of emerging, contemporary and historical interest. An abbreviated list of subjects explored in the seminars includes: global energy resources, energy generation technologies (present and future), energy storage options, environmental impacts and climate change mitigation, energy policy, and energy delivery economics and systems. Seminar speakers will be distinguished practicing engineers and executives from industry and government as well as faculty members from several departments at Cornell, and other academic institutions.

- **ECE 5880 - Energy Seminar II**
    Energy Seminars will continue to explore energy-related topics of emerging, contemporary and historical interest. An abbreviated list of subjects explored in the seminars includes: global energy resources, energy generation technologies (present and future), energy storage options, environmental impacts and climate change mitigation, energy policy, and energy delivery economics and systems. Seminar speakers will be distinguished practicing engineers and executives from industry and government as well as faculty members from several departments at Cornell, and other academic institutions.

- **MAE 5010 - FutureEnergy Systems**
    Critically examines the technology of energy systems that will be acceptable in a world faced with global climate change, local pollution, and declining supplies of oil. The focus is on renewable energy sources (wind, solar, biomass), but other non-carbon-emitting sources (nuclear) and lowered-carbon sources (co-generative gas turbine plants, fuel cells) also are studied. Both the devices and the overall systems are analyzed. The course explains calculations to support capacity, efficiency, and productivity of renewable energy. Cost and economics of renewables are explored as well, along with the connection to U.S. and global climate and energy policy.