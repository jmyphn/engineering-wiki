---
layout: default
title: Automotive & EV Engineering Page
permalink: /mae-auto/
---
\
\
[Home]({{ '/' | relative_url }}) → [Mechanical Engineering]({{ '/maemajor/' | relative_url }}) → Automotive & EV Engineering
# MAE Major - Automotive & EV Engineering 🏎️
Specialized study on the dynamics and propulsion of ground vehicles. Focuses on vehicle stability, electric powertrains, internal combustion, and the integration of IoT/sensors for modern connected vehicles.

## Flow Map
```mermaid
flowchart TD
  subgraph A1[Prerequisites]
    A1a[MAE 2030 Dynamics]
    A1b[MAE 2210 Thermodynamics]
    A1c[Phys 2213 E&M]
  end

  subgraph B1[Core Fundamentals]
    B1a[MAE 3260 System Dynamics]
    B1b[MAE 3250 Machine Design]
    B1c[MAE 3780 Mechatronics]
  end

  subgraph C1[Vehicle Systems]
    C1a[MAE 4250 Automotive Engineering]
    C1b[MAE 4780 Feedback Control]
    C1c[MAE 4230 Intermediate Fluids]
  end

  subgraph D1[Propulsion & Power]
    D1a[MAE 5430 Combustion Processes]
    D1b[MAE 5010 Future Energy Systems]
    D1c[MAE 4272 Fluids/Heat Lab]
  end

  subgraph E1[Connected & Practical]
    E1a[MAE 4220 Intro to IoT]
  end

  %% Flow Connections
  A1a --> B1a
  A1b --> D1a
  A1c --> B1c

  B1a --> C1a
  B1a --> C1b
  B1b --> C1a
  B1c --> E1a
  B1c --> D1b

  C1c --> C1a
  C1c --> D1c
```

## Prerequisite Courses:
- **Dynamics** — Newton’s laws, rigid body kinematics, and kinetics (essential for vehicle stability).
- **Thermodynamics** — Power cycles, efficiency, and heat engines (ICE and battery thermal management).
- **Physics (E&M)** — Circuits and electromagnetic fields (critical for EV motors).

## Core Courses:

- **MAE 4250 - Automotive Engineering**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Vehicle performance (acceleration/braking), handling/cornering stability, tire mechanics, and suspension design.</li>
    <li>Essential? Yes—this is the definitive course for the track.</li>
    <li>Recommended workflow: Senior Fall.</li>
    <li>Prereqs and why: System Dynamics (modeling mass-spring-damper).</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 3260 - System Dynamics**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Mathematical modeling of suspension systems, vibration isolation, and frequency response of mechanical systems.</li>
    <li>Essential? Yes—fundamental for understanding ride quality and stability.</li>
    <li>Recommended workflow: Junior year.</li>
    <li>Prereqs and why: Dynamics, Diff Eq.</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 3250 - Analysis of Mechanical & Aerospace Structures (Machine Design)**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Stress analysis, fatigue failure, gears, bearings, and transmission component design.</li>
    <li>Essential? Critical for chassis and powertrain mechanical design.</li>
    <li>Recommended workflow: Junior year.</li>
    <li>Prereqs and why: Statics/Mechanics of Materials.</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 5430 - Combustion Processes**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Internal combustion engine (ICE) cycles, flame propagation, knock, and emissions control.</li>
    <li>Essential? Yes for traditional automotive and hybrid powertrains.</li>
    <li>Recommended workflow: Senior/M.Eng.</li>
    <li>Prereqs and why: Thermodynamics.</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 5010 - Future Energy Systems**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Battery chemistry, energy storage density, fuel cells, and electric grid integration for EVs.</li>
    <li>Essential? Critical for Electric Vehicle (EV) specialization.</li>
    <li>Recommended workflow: Senior Spring.</li>
    <li>Prereqs and why: Thermodynamics.</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4780 - Feedback Control Systems**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: PID control, cruise control logic, lane-keeping algorithms, and stability augmentation.</li>
    <li>Essential? Highly recommended for ADAS (Advanced Driver Assistance Systems).</li>
    <li>Recommended workflow: Senior Fall.</li>
    <li>Prereqs and why: System Dynamics.</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4230 - Intermediate Fluid Mechanics**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Aerodynamic drag reduction, boundary layers, and airflow over bodies (vehicle exterior aerodynamics).</li>
    <li>Essential? Key for performance and fuel efficiency engineering.</li>
    <li>Recommended workflow: Senior year.</li>
    <li>Prereqs and why: Intro Fluids.</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4220 - Introduction to Internet of Things (IoT)**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Vehicle-to-Everything (V2X) communication, sensor networks, and data handling for connected cars.</li>
    <li>Essential? Good for modern "Smart Vehicle" tracks.</li>
    <li>Recommended workflow: Senior elective.</li>
    <li>Prereqs and why: Mechatronics.</li>
    </ul>
    </div>
  </div>
  </details>