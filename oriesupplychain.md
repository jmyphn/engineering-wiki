---
layout: default
title: Supply Chain & Operations Page
permalink: /oriemajor-supplychain/
---
\
\
[Home]({{ '/' | relative_url }}) → [Operations Research & Engineering]({{ '/oriemajor/' | relative_url }}) → Supply Chain & Operations

# ORIE Major - Supply Chain & Operations
Field of study on the design & execution of supply chains in various industries.

## Flow Map
```mermaid
flowchart TD

  %% ===== PREREQS =====
  subgraph A1[Prerequisite Courses]
    A1a[CS 1110/1112 Intro to Python]
    A1b[MATH 2210/2940 Linear Algebra]
    A1c[MATH 1920/2930 Multivariable Calculus]
    A1d[ENGRD 2700 or ORIE 3500 Probability & Statistics]
    A1e[ORIE 3300 Optimization I]
    A1f[ORIE 3510 Stochastic Processes]
  end

  %% ===== FOUNDATIONS =====
  subgraph B1[Foundations in Supply Chain & Decision Modeling]
    B1a[ORIE 4126 Principles of Supply Chain Management]
    B1b[ORIE 4820 Data-Driven Decision Modeling & Analysis]
  end

  %% ===== SYSTEMS & APPLICATIONS =====
  subgraph C1[Manufacturing & Service Systems]
    C1a[ORIE 4100 Manufacturing Systems Design]
    C1b[ORIE 4130 Service System Modeling & Design]
  end

  A1a --> B1a
  A1e --> B1a
  A1f --> B1a

  A1d --> B1b
  A1e --> B1b

  A1d --> C1b
  A1f --> C1b

```

## Prerequisite Courses:
- Programming in Python — data wrangling, implementation of supply chain and operations models
- Linear Algebra (e.g., MATH 2210/2940) — model representations, SVD/PCA, optimization basics
- Calculus (single & multi-variable) — gradients, optimization, continuous models
- Probability & Statistics (e.g., ORIE 3500/ENGRD 2700) — demand uncertainty, performance metrics, and data-driven analysis.
- Optimization -- linear programming and basic optimization, useful for inventory models, network flows, and decision models
- Stochastic Processes -- queueing, arrival processes, and Markov models

## Core Courses:  
- **ORIE 4100 - Manufacturing Systems Design: A Consulting Boot Camp**
  - What you'll learn: design and analysis of manufacturing logistics systems, collaboration in real-world industry projects
  - Essential? Recommended for students interested in consulting and project management.
  - Recommended workflow: Take after some intro probability/stats courses. Taking as an underclassmen could help with job search.
  - Prereqs and why: None explicitly. 
- **ORIE 4126 - Principles of Supply Chain Management**
  - What you'll learn: key principles of effective supply chains through a collection of cases. 
  - Essential? Yes -- introduces basic analysis & design of global supply chains, along with analytical techniques.
  - Recommended workflow: take as elective junior or senior year.
  - Prereqs and why: mathematical programming and stochastic processes, as well as familiarity with Python to complete assignments.
- **ORIE 4130 - Service System Modeling & Design**
  - What you'll learn: techniques for analysis and design of service systems like contact centers, airlines, insurance, and healthcare.
  - Essential? Recommended for real-world applications of stochastic processes.
  - Recommended workflow: ORIE elective, take after prerequisities.
  - Prereqs and why: Probability and statistics helpful for understanding random nature of service systems, as well as stochastic processes.
- **ORIE 4820 - Data-Driven Decision Modeling and Analysis**
  - What you'll learn: classical modeling techniques with modern computational tools, particularly Excel, Python, and Power BI.
  - Essential? Yes -- helpful for consulting and data analytics roles.
  - Recommended workflow: before or during junior year; helpful for interview and career prep.
  - Prereqs and why: basic probability and statistics, as well as linear programming; will be solved using computational tools.