---
layout: default
title: Robotics & Mechatronics Page
permalink: /mae-robotics/
---
\
\
[Home]({{ '/' | relative_url }}) → [Mechanical Engineering]({{ '/maemajor/' | relative_url }}) → Robotics & Mechatronics
# MAE Major - Robotics & Mechatronics 🤖
Interdisciplinary field combining mechanical systems with electronics and software control. Focuses on autonomous mobile robots, feedback control systems, sensors/actuators, and machine learning applied to physical systems.

## Flow Map
```mermaid
flowchart TD
  subgraph A1[Prerequisites]
    A1a[Intro to Computing CS1110]
    A1b[Calculus / Linear Algebra]
    A1c[Physics: E&M]
  end

  subgraph B1[Core MAE]
    B1a[MAE 2030 Dynamics]
    B1b[MAE 1170 Intro to MechE]
    B1c[MAE 3780 Mechatronics]
  end

  subgraph C1[Intelligence & Control]
    C1a[MAE 3260 System Dynamics]
    C1b[MAE 3200 Intro to ML for MechE]
    C1c[MAE 4780 Feedback Control Systems]
  end

  subgraph D1[Mobile Systems]
    D1a[MAE 4180 Autonomous Mobile Robots]
    D1b[MAE 4190 Fast Robots]
  end

  subgraph E1[Hardware]
    E1a[MAE 4320 Micro Sensors & Actuators]
    E1b[MAE 4220 Intro to IoT]
  end

  subgraph F1[Advanced Robotics]
    F1a[MAE 4760 Foundations of Robotics]
    F1b[MAE 5920 Systems Analysis & Opt]
  end

  A1a --> C1b
  A1b --> B1a
  A1c --> B1c

  B1a --> C1a
  B1b --> B1c
  B1c --> D1a
  B1c --> D1b
  B1c --> E1a

  C1a --> C1c
  C1c --> F1a
  C1b --> D1a

  D1a --> F1a
  D1b --> F1a
  E1b --> F1b
```
## Prerequisite Courses:
- **Intro to Computing (Python)** — Programming logic, data structures, and algorithms (critical for all robotics).
- **Linear Algebra** — Coordinate transformations, state-space representations, matrix operations.
- **Physics (Electricity & Magnetism)** — Circuits, sensors, electromagnetic actuation.
- **Dynamics** — Rigid body motion, kinematics, kinetics (Newton/Euler).
- **Differential Equations** — Modeling physical systems (mass-spring-damper, RLC circuits).

## Core Courses:

- **MAE 3780 - Mechatronics**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Microcontrollers (Arduino/STM32), sensors, actuators, circuit design, and embedded C programming.</li>
    <li>Essential? Yes—this is the foundational hardware/software bridge course.</li>
    <li>Recommended workflow: Sophomore Spring or Junior Fall.</li>
    <li>Prereqs and why: Physics E&M (circuits), Intro CS (coding logic).</li>
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
    <li>What you'll learn: Modeling mechanical/electrical systems, transfer functions, frequency response, and time-domain analysis.</li>
    <li>Essential? Yes—prerequisite for all control theory.</li>
    <li>Recommended workflow: Junior year.</li>
    <li>Prereqs and why: Dynamics and Diff Eq (math foundation).</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 3200 - Introduction to Machine Learning for Mechanical Engineers**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Supervised/unsupervised learning, neural networks, and regression specifically applied to physical data.</li>
    <li>Essential? Highly recommended for modern autonomous systems.</li>
    <li>Recommended workflow: Junior year.</li>
    <li>Prereqs and why: Linear Algebra, Probability, Coding.</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4180 - Autonomous Mobile Robots**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Localization (Kalman Filters, Monte Carlo), Mapping (SLAM), Path Planning (A*), and Computer Vision.</li>
    <li>Essential? The flagship robotics course for autonomy.</li>
    <li>Recommended workflow: Senior Fall.</li>
    <li>Prereqs and why: Mechatronics (hardware), Probability (for filters).</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4190 - Fast Robots**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Building a high-speed autonomous car, aggressive maneuvering, state estimation at high frequency.</li>
    <li>Essential? Great for practical, hands-on integration skills.</li>
    <li>Recommended workflow: Senior Spring; often follows 4180.</li>
    <li>Prereqs and why: Mechatronics, Feedback Control.</li>
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
    <li>What you'll learn: PID control, root locus, Bode plots, stability margins, and compensator design.</li>
    <li>Essential? Yes—fundamental for making robots stable and precise.</li>
    <li>Recommended workflow: After System Dynamics.</li>
    <li>Prereqs and why: System Dynamics (Laplace transforms).</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4760 - Foundations of Robotics**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Kinematics (Forward/Inverse), Dynamics (Lagrangian), Jacobians, and trajectory generation for robot arms.</li>
    <li>Essential? Yes for manipulation and robotic arms.</li>
    <li>Recommended workflow: Senior year.</li>
    <li>Prereqs and why: Linear Algebra (rotation matrices), Dynamics.</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4320 - Integrated Micro Sensors and Actuators**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: MEMS technology, micro-fabrication, capacitive sensing, and piezoelectric actuation.</li>
    <li>Essential? Elective for hardware-focused students.</li>
    <li>Recommended workflow: Senior/M.Eng elective.</li>
    <li>Prereqs and why: Physics, Mechatronics basics.</li>
    </ul>
    </div>
  </div>
  </details>

- **MAE 4220 - Introduction to Internet of Things**
  <details>
  <summary>Details</summary>
  <div class="beamer-block">
    <div class="beamer-block-content">
    <ul>
    <li>What you'll learn: Connectivity (WiFi/BLE/LoRa), cloud data handling, edge computing, and distributed sensing.</li>
    <li>Essential? Good for connected systems/smart devices.</li>
    <li>Recommended workflow: Senior elective.</li>
    <li>Prereqs and why: Mechatronics or Embedded coding.</li>
    </ul>
    </div>
  </div>
  </details>
