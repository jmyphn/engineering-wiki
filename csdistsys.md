---
layout: default
title: Distributed Systems Page
permalink: /csmajor-distsys/
---
\
\
[Home]({{ '/' | relative_url }}) → [Computer Science]({{ '/csmajor/' | relative_url }}) → Distributed Systems
# CS Major - Distributed Systems 🌎
Field of study on the design, construction, and analysis of large-scale systems.

## Flow Map
```mermaid
flowchart TD
  subgraph A1[Prerequisites]
    A1a[Systems Programming]
    A1b[Operating Systems]
    A1c[Computer Networks]
    A1d[Databases]
    A1e[Probability/Stats]
  end

  subgraph B1[Core]
    B1a[CS 4414 Systems Programming]
    B1b[CS 4410/4411 Operating Systems]
    B1c[CS 4450 Intro to Networks]
    B1d[CS 4320/4321 Databases]
  end

  subgraph C1[Distributed]
    C1a[CS 5414 Distributed Systems]
  end

  subgraph D1[Cloud]
    D1a[CS 5416 Cloud Computing & ML Hosting]
  end

  subgraph E1[Security]
    E1a[CS 5430 System Security]
  end

  subgraph F1[ML Systems]
    F1a[CS 5470 Systems for Large-Scale ML]
  end

  subgraph G1[Advanced]
    G1a[CS 6410 Advanced Systems]
    G1b[CS 6412 Advanced Topics in OS]
  end

  subgraph H1[Networking]
    H1a[CS 6450 Advanced Networking]
  end

  subgraph I1[Datacenter]
    I1a[ECE 6960 Datacenter Networking Systems]
  end

  A1a --> B1a
  A1b --> B1b
  A1c --> B1c
  A1d --> B1d
  B1a --> C1a
  B1b --> C1a
  B1c --> C1a
  B1d --> C1a
  C1a --> D1a
  C1a --> E1a
  C1a --> F1a
  C1a --> G1a
  C1a --> H1a
  H1a --> I1a
```

## Prerequisite Courses:
- Programming and Systems Programming (C/C++/Rust) — concurrency, sockets, correctness
- Data Structures & Algorithms — complexity, correctness, distributed algorithms reasoning
- Operating Systems (concepts) — processes/threads, memory, filesystems on single nodes
- Computer Networks (intro) — TCP/IP, latency, reliability, congestion control
- Databases (intro) — transactions, isolation, indexing, query planning
- Probability/Statistics — SLAs/SLOs, reliability, backoff/retry math, performance analysis

## Core Courses:
- **CS 4320 - Intro to Databases**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Relational models, SQL, transactions, indexing, and query optimization.</li>
    <li>- Essential? Yes—databases underpin most distributed systems.</li>
    <li>- Recommended workflow: Take early; build a small app with real queries and indexes.</li>
    <li>- Prereqs and why: Data structures/algorithms (for query plans/indexes).</li>
    </ul>
  </details>

- **CS 4321 - Databases Practicum**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Implementation-focused DB components and advanced SQL usage.</li>
    <li>- Essential? Recommended to cement DB fundamentals.</li>
    <li>- Recommended workflow: Co-enroll with 4320; prioritize the project work.</li>
    <li>- Prereqs and why: 4320 concepts; strong programming.</li>
    </ul>
  </details>

- **CS 4410 - Operating Systems**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Processes, scheduling, memory, filesystems—core for understanding nodes in a cluster.</li>
    <li>- Essential? Yes for backend/distributed roles.</li>
    <li>- Recommended workflow: Before/alongside core distributed systems.</li>
    <li>- Prereqs and why: C/concurrency; architecture basics.</li>
    </ul>
  </details>

- **CS 4411 - Operating Systems Practicum**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Hands-on OS labs that map to real server behavior.</li>
    <li>- Essential? Recommended to deepen OS understanding.</li>
    <li>- Recommended workflow: With 4410.</li>
    <li>- Prereqs and why: C debugging, 4410.</li>
    </ul>
  </details>

- **CS 4414 - Systems Programming**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Low-level networking, concurrency, and robust systems development.</li>
    <li>- Essential? Recommended setup for distributed/back-end.</li>
    <li>- Recommended workflow: Before 5414; build networked services.</li>
    <li>- Prereqs and why: Data structures; comfort with memory/concurrency.</li>
    </ul>
  </details>

- **CS 4450 - Intro to Computer Networks**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: TCP/IP, routing, congestion control, application protocols.</li>
    <li>- Essential? Yes—networking is the substrate for distributed systems.</li>
    <li>- Recommended workflow: Before or alongside 5414.</li>
    <li>- Prereqs and why: OS/sockets helpful; probability for performance analysis.</li>
    </ul>
  </details>

- **CS 5414 - Distributed Systems**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Replication, consensus, fault tolerance, consistency, and distributed coordination.</li>
    <li>- Essential? Core course for the concentration.</li>
    <li>- Recommended workflow: After OS and networks; implement labs like Raft/KV store.</li>
    <li>- Prereqs and why: Concurrency (for correctness), networking (for RPC), algorithms (for proofs/invariants).</li>
    </ul>
  </details>

- **CS 5416 - Cloud Computing and ML Hosting**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Cloud primitives, containers, orchestration, service meshes, ML serving.</li>
    <li>- Essential? Recommended for modern infra/platform roles.</li>
    <li>- Recommended workflow: After 5414; deploy real services on cloud-like platforms.</li>
    <li>- Prereqs and why: OS, networking, scripting/automation.</li>
    </ul>
  </details>

- **CS 5430 - System Security**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Threat models, vulnerabilities, secure design, and practical defenses.</li>
    <li>- Essential? Recommended—security is integral to production systems.</li>
    <li>- Recommended workflow: Anywhere after systems programming.</li>
    <li>- Prereqs and why: OS and networking fundamentals.</li>
    </ul>
  </details>

- **CS 5470 - Systems for Large-Scale Machine Learning**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Distributed training/inference, data pipelines, accelerators, and scaling ML systems.</li>
    <li>- Essential? Elective for ML infra/platform roles.</li>
    <li>- Recommended workflow: After 5414 and ML basics; run distributed experiments.</li>
    <li>- Prereqs and why: ML basics, OS/networking, and parallel computing helpful.</li>
    </ul>
  </details>

- **CS 6410 - Advanced Systems**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Research papers in systems; OS, storage, networking, and distributed topics.</li>
    <li>- Essential? Advanced elective for research-oriented paths.</li>
    <li>- Recommended workflow: After 5414; replicate or extend a paper result.</li>
    <li>- Prereqs and why: Strong systems background; reading and experimentation skills.</li>
    </ul>
  </details>

- **CS 6412 - Advanced Topics in Operating Systems**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Deep dives into OS topics such as virtualization, scheduling, and isolation.</li>
    <li>- Essential? Elective for OS-heavy interests.</li>
    <li>- Recommended workflow: After 4410/6410.</li>
    <li>- Prereqs and why: 4410 concepts; strong C and debugging.</li>
    </ul>
  </details>

- **CS 6450 - Advanced Computer Networking**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Advanced routing, data center networks, congestion control, programmable networks.</li>
    <li>- Essential? Elective for network/infra specialists.</li>
    <li>- Recommended workflow: After 4450.</li>
    <li>- Prereqs and why: 4450 networking fundamentals; probability/perf analysis helpful.</li>
    </ul>
  </details>

- **ECE 6960 - Datacenter Networking Systems**
  <details>
  <summary>Details</summary>
    <ul>
    <li>- What you'll learn: Data center fabrics, transport, telemetry, and reliability at scale.</li>
    <li>- Essential? Advanced elective for data center/network-focused roles.</li>
    <li>- Recommended workflow: After core networking; pair with a measurement project.</li>
    <li>- Prereqs and why: Strong networking and systems background.</li>
    </ul>
  </details>