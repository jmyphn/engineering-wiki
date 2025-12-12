---
layout: default
title: Materials & Manufacturing Page
permalink: /mae-materials/
---
\
\
[Home]({{ '/' | relative_url }}) → [Mechanical Engineering]({{ '/maemajor/' | relative_url }}) → Materials & Manufacturing
# MAE Major - Materials & Manufacturing 🔬
Field of study connecting the atomic structure of matter to macroscopic mechanical properties and production. Covers composite materials, additive manufacturing (3D printing), digital manufacturing, and product design.

## Flow Map
```mermaid
flowchart TD
  subgraph A1[Prerequisites]
    A1a[Gen Chem & Physics]
    A1b[Math Core]
  end

  subgraph B1[Fundamentals]
    B1a[MAE 2020 Statics & Mechanics]
    B1b[MAE 2250 Mechanical Design]
    B1c[MAE 3130 Atomic Structure of Matter]
  end

  subgraph C1[Analysis & Mechanics]
    C1a[MAE 3270 Mechanics of Materials]
    C1b[MAE 4130 Composite Structures]
  end

  subgraph D1[Manufacturing Processes]
    D1a[MAE 4240 Materials Processing]
    D1b[MAE 4450 Additive Manufacturing]
  end

  subgraph E1[Product Realization]
    E1a[MAE 4630 Adv. Product Design]
    E1b[MAE 4341 Innovative Product Design]
    E1c[MAE 5260 Design for Mfg/Assembly]
    E1d[MAE 5210 Dimensional Tolerancing]
  end

  %% Flow Connections
  A1a --> B1c
  A1b --> B1a

  B1a --> C1a
  B1b --> E1c
  
  B1c --> D1a
  C1a --> C1b
  C1a --> D1a
  C1a --> D1b

  D1a --> E1a
  D1b --> E1b
  C1b --> E1d

  E1a --> E1c
```

## Prerequisite Courses:
- **General Chemistry** — Atomic bonding, periodic trends, and chemical reactions (basis for material properties).
- **Physics (Mechanics)** — Forces, equilibrium, and energy.
- **Math Core** — Calculus and Differential Equations for stress analysis.

## Core Courses:

- **MAE 2020 - Statics and Mechanics of Solids**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Free body diagrams, stress/strain relationships, beam bending, torsion, and failure criteria (Von Mises).</li>
    <li>Essential? Yes—the absolute foundation of mechanical engineering.</li>
    <li>Recommended workflow: Sophomore Fall.</li>
    <li>Prereqs and why: Math/Physics.</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 2250 - Mechanical Synthesis (Machine Design)**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Design of mechanisms, fatigue analysis, bearings, gears, and component reliability.</li>
    <li>Essential? Yes—connects theory to practical machinery.</li>
    <li>Recommended workflow: Sophomore Spring.</li>
    <li>Prereqs and why: Statics (MAE 2020).</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 3130 - Atomic and Molecular Structure of Matter**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Crystal lattices, defects, phase diagrams, and how atomic structure dictates strength and conductivity.</li>
    <li>Essential? Yes—bridges the gap between Chemistry and Engineering.</li>
    <li>Recommended workflow: Junior Fall.</li>
    <li>Prereqs and why: Chemistry, Physics.</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 3270 - Mechanics of Engineering Materials**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Plasticity, fracture mechanics, fatigue life prediction, and time-dependent deformation (creep).</li>
    <li>Essential? Yes—critical for preventing structural failure.</li>
    <li>Recommended workflow: Junior Spring.</li>
    <li>Prereqs and why: Statics & Mechanics (MAE 2020).</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4240 - Materials Processing for Mechanical Engineers**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: How things are made—casting, forging, rolling, extrusion, and injection molding physics.</li>
    <li>Essential? Highly recommended for understanding how design impacts production.</li>
    <li>Recommended workflow: Senior Fall.</li>
    <li>Prereqs and why: Mechanics of Materials, Atomic Structure.</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4130 - Mechanics of Composite Structures**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Anisotropic materials, carbon fiber laminates, sandwich structures, and failure modes in composites.</li>
    <li>Essential? Critical for Aerospace and high-performance Auto sectors.</li>
    <li>Recommended workflow: Senior/M.Eng.</li>
    <li>Prereqs and why: Mechanics of Materials.</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4450 - Introduction to Additive Manufacturing (3D Printing)**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: FDM, SLA, SLS, metal sintering, and the material science behind layer-by-layer adhesion.</li>
    <li>Essential? The modern standard for prototyping and complex geometry.</li>
    <li>Recommended workflow: Senior elective.</li>
    <li>Prereqs and why: Mechanics of Materials.</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4630 - Advanced Product Design**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: The full design lifecycle—user needs, concept generation, prototyping, and design refinement.</li>
    <li>Essential? Capstone-level design experience.</li>
    <li>Recommended workflow: Senior/M.Eng.</li>
    <li>Prereqs and why: Materials Processing (understanding constraints).</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 5260 - Design for Manufacture and Assembly (DFMA)**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Modifying designs to reduce part count, cost estimation, and optimizing for automated assembly.</li>
    <li>Essential? Vital for mass-production engineering roles.</li>
    <li>Recommended workflow: M.Eng / Senior Spring.</li>
    <li>Prereqs and why: Mechanical Design (MAE 2250).</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 5210 - Dimensional Tolerancing and Metrology**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: GD&T (Geometric Dimensioning and Tolerancing), measurement uncertainty, and quality control.</li>
    <li>Essential? Yes—drawings are the language of engineering, and this teaches you to speak it fluently.</li>
    <li>Recommended workflow: Senior/M.Eng.</li>
    <li>Prereqs and why: Composite Structures or Manufacturing background.</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4341 - Innovative Product Design via Digital Manufacturing**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Leveraging digital tools (CAD/CAM/CAE) to drive innovation and rapid iteration in product development.</li>
    <li>Essential? Great for entrepreneurial engineers.</li>
    <li>Recommended workflow: Senior Spring.</li>
    <li>Prereqs and why: Additive Manufacturing.</li>
    </ul>
    </div>
  </div>
  </details>