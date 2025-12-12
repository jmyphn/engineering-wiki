---
layout: default
title: Aerospace Engineering Page
permalink: /mae-aero/
---
\
\
[Home]({{ '/' | relative_url }}) → [Mechanical Engineering]({{ '/maemajor/' | relative_url }}) → Aerospace Engineering
# MAE Major - Aerospace Engineering 🚀
Field of study focused on the design, analysis, and mechanics of airborne and spaceborne vehicles. Covers aerodynamics, propulsion, orbital mechanics, and flight dynamics.

## Flow Map
```mermaid
flowchart TD
  subgraph A1[Prerequisites]
    A1a[Calculus I-III / Diff Eq]
    A1b[Physics: Mechanics]
    A1c[Physics: Thermo]
  end

  subgraph B1[Core MAE]
    B1a[MAE 2030 Dynamics]
    B1b[MAE 2210 Thermodynamics]
    B1c[MAE 3230 Intro Fluid Mechanics]
    B1d[MAE 3270 Mech. of Eng. Materials]
  end

  subgraph C1[Aero Fundamentals]
    C1a[MAE 3050 Intro to Aeronautics]
    C1b[MAE 3260 System Dynamics]
  end

  subgraph D1[Flight Dynamics]
    D1a[MAE 4070 Dynamics of Flight Vehicles]
    D1b[MAE 4060 Intro to Spaceflight Mechanics]
  end

  subgraph E1[Propulsion]
    E1a[MAE 4510 Propulsion of Aircraft & Rockets]
    E1b[MAE 4540 Propulsion of Spacecraft]
  end

  subgraph F1[Space Systems]
    F1a[MAE 4160 Spacecraft Tech & Systems Arch]
    F1b[MAE 5390 Cybersecurity for Aerospace]
  end

  subgraph G1[Structures]
    G1a[MAE 4700 Finite Element Analysis]
    G1b[MAE 4130 Mechanics of Composite Structures]
  end

  A1a --> B1a
  A1a --> B1b
  A1a --> B1c
  A1b --> B1a
  A1c --> B1b

  B1a --> C1b
  B1b --> C1a
  B1c --> C1a
  B1d --> G1a
  B1d --> G1b

  C1a --> D1a
  C1a --> D1b
  C1a --> E1a

  D1b --> E1b
  D1b --> F1a
  D1a --> F1b
  E1b --> F1a
```

## Prerequisite Courses:
- **Multivariable Calculus & Differential Equations** — fluid flow, orbital trajectories, heat equations
- **Physics (Newtonian Mechanics)** — force balances, conservation of momentum/energy
- **Thermodynamics** — cycles, efficiency, gas laws (crucial for propulsion)
- **Fluid Mechanics** — Navier-Stokes, boundary layers, compressible flow
- **Dynamics** — rigid body motion, reference frames, vibrations
- **Statics/Mechanics of Materials** — stress/strain, material failure modes

## Core Courses:

- **MAE 3050 - Introduction to Aeronautics**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Standard atmosphere, airfoils, finite wings, drag polar, and aircraft performance/stability.</li>
    <li>Essential? Yes—the gateway course for the entire concentration.</li>
    <li>Recommended workflow: Take immediately after MAE 3230 (Fluids).</li>
    <li>Prereqs and why: Fluid Mechanics (Bernoulli's principle, viscosity).</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4060 - Introduction to Spaceflight Mechanics**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Two-body problem, orbital maneuvers (Hohmann transfer), interplanetary trajectories, and restricted three-body problem.</li>
    <li>Essential? Yes—fundamental for any space-related role.</li>
    <li>Recommended workflow: Junior/Senior year; pairs well with Propulsion.</li>
    <li>Prereqs and why: Dynamics (Newton's laws, angular momentum conservation).</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4070 - Dynamics of Flight Vehicles**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Equations of motion for rigid aircraft, stability derivatives, longitudinal/lateral modes, and autopilot control.</li>
    <li>Essential? Core for atmospheric flight paths (GNC engineers).</li>
    <li>Recommended workflow: After System Dynamics (MAE 3260).</li>
    <li>Prereqs and why: System Dynamics (transfer functions, eigenvalues for stability).</li>
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
    <li>What you'll learn: Anisotropic elasticity, laminate theory, failure criteria for carbon fiber/epoxy structures.</li>
    <li>Essential? Highly recommended for structural roles (Boeing/SpaceX).</li>
    <li>Recommended workflow: Senior elective.</li>
    <li>Prereqs and why: Mechanics of Materials (stress tensors).</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4160 - Spacecraft Technology and Systems Architecture**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Space mission design, subsystems (power, thermal, comms, ADCS), and link budgets.</li>
    <li>Essential? The "Capstone" of the space track.</li>
    <li>Recommended workflow: Senior year; synthesize knowledge from all previous courses.</li>
    <li>Prereqs and why: Spaceflight Mechanics (orbits dictate power/thermal environments).</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4510 - Propulsion of Aircraft and Rockets**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Turbojets, turbofans, ramjets, nozzle flow, and chemical rocket basics.</li>
    <li>Essential? Yes for propulsion engineers.</li>
    <li>Recommended workflow: After Thermodynamics and Compressible Flow.</li>
    <li>Prereqs and why: Thermodynamics (Brayton cycles), Fluids (shock waves).</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4540 - Propulsion of Spacecraft**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Electric propulsion (Hall thrusters, ion engines), nuclear thermal, and advanced chemical propulsion.</li>
    <li>Essential? Elective for deep space/satellite propulsion specialization.</li>
    <li>Recommended workflow: After MAE 4060 or 4510.</li>
    <li>Prereqs and why: Physics E&M (for electric propulsion fields), Thermodynamics.</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4700 - Finite Element Analysis**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Numerical solutions to stress/strain problems, meshing, and commercial FEA software usage (ANSYS/Abaqus).</li>
    <li>Essential? Industry standard skill for structural validation.</li>
    <li>Recommended workflow: Senior year or concurrent with design teams.</li>
    <li>Prereqs and why: Linear Algebra (matrix solvers), Mechanics of Materials.</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 5390 - Cybersecurity for Cyber-Physical and Aerospace Systems**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Attack surfaces in avionics, spoofing, jamming, and securing flight software.</li>
    <li>Essential? Niche but rapidly growing importance.</li>
    <li>Recommended workflow: Advanced elective for systems-focused students.</li>
    <li>Prereqs and why: Basic coding and systems understanding.</li>
    </ul>
    </div>
  </div>
  </details>