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
  subgraph A1[Prerequisites]
    A1a[CS 1110/1112<br/>Intro Python]
    A1b[CS 2110<br/>OO Programming]
    A1c[Linear Algebra<br/>MATH 2210/2940]
    A1d[Probability & Stats<br/>ENGRD 2700 or ORIE 3500]
  end

  %% ===== FOUNDATIONS =====
  subgraph B1[Foundations in Data & Optimization]
    B1a[ORIE 3320<br/>Optimization for AI]
    B1b[ORIE 3741<br/>Learning with Big Messy Data]
  end

  %% ===== CORE METHODS =====
  subgraph C1[Core Machine Learning & Inference]
    C1a[ORIE 4740<br/>Statistical Data Mining I]
    C1b[ORIE 4750<br/>Foundations of Causal Inference<br/>(AY 26–27 first offering)]
  end

  %% ===== ADVANCED DECISION SYSTEMS =====
  subgraph D1[Advanced Intelligent Decision Systems]
    D1a[ORIE 4570<br/>Reinforcement Learning<br/>with OR Applications]
  end

  %% ===== PATH LINKS =====

  A1a --> B1b
  A1a --> B1a
  A1b --> B1b
  A1c --> B1a
  A1d --> B1a
  A1d --> B1b

  B1a --> C1a
  B1b --> C1a
  C1a --> C1b
  C1a --> D1a
  C1b --> D1a
```

## Prerequisite Courses:
- Programming in Python — data wrangling, numerical computing, notebooks
- Linear Algebra (e.g., MATH 2210/2940) — model representations, SVD/PCA, optimization basics
- Calculus (single & multi-variable) — gradients, optimization, continuous models
- Probability & Statistics (e.g., ORIE 3500/ENGRD 2700) — inference, estimation, hypothesis testing
- Data Structures & Algorithms — efficient processing and scalability

## Core Courses:  
- **ORIE 4100 - Manufacturing Systems Design: A Consulting Boot Camp**
  - What you'll learn: Python data stack, basic statistics, regression/classification, and end-to-end DS workflow.
  - Essential? Yes—intro foundation for engineers entering DS/ML.
  - Recommended workflow: Take early; build a small analysis project with proper documentation.
  - Prereqs and why: Intro programming; basic calculus helps.
- **ORIE 4126 - Principles of Supply Chain Management**
  - What you'll learn: Probability, random variables, estimation, hypothesis testing—core for inference.
  - Essential? Yes—statistics underpins DS rigor and experimentation.
  - Recommended workflow: Before applied DS/ML courses.
  - Prereqs and why: Calculus; comfort with algebraic manipulation.
- **ORIE 4130 - Service System Modeling & Design**
  - What you'll learn: Data wrangling, EDA, visualization, modeling basics, and communication of results.
  - Essential? Recommended if you want a broader intro with viz/communication.
  - Recommended workflow: Early; pair with a project using real datasets.
  - Prereqs and why: Programming fundamentals; basic stats helpful.
- **ORIE 4820 - Data-Driven Decision Modeling and Analysis**
  - What you'll learn: Practical DS at scale—messy data, pipelines, experiment design, and deployment.
  - Essential? Recommended for industry readiness.
  - Recommended workflow: After an intro DS/ML course; focus on reproducibility.
  - Prereqs and why: Python data stack; basic ML and SQL helpful.
- **ORIE 6336 - Integer Programming**
  - What you'll learn: Efficient algorithms and systems for DS; performance-aware data processing and learning.
  - Essential? Elective bridging algorithms/systems with DS.
  - Recommended workflow: After core DS and algorithms; profile and optimize pipelines.
  - Prereqs and why: Algorithms, data structures, and Python/SQL tooling.