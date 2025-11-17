---
layout: default
title: Data, Decisions, and AI Page
permalink: /oriemajor-datadecisions/
---
\
\
[Home]({{ '/' | relative_url }}) → [Operations Research & Engineering]({{ '/oriemajor/' | relative_url }}) → Data, Decisions, and AI

# ORIE Major - Data, Decisions, and AI         
Interdisciplinary field of study that uses algorithms and statistics to extract meaningful insights from large datasets.

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
- **ORIE 3320 - Optimization for AI**
  - What you'll learn: theory, algorithms, and applications of nonlinear optimization
  - Essential? Yes—real-world applications of optimization in machine learning & OR
  - Recommended workflow: Take as ORIE elective
  - Prereqs and why: calculus and linear alegbra; necessary for solving optimization problems
- **ORIE 3741 - Learning with Big messay Data**
  - What you'll learn: scalable, robust methods for learning from large datasets
  - Essential? Yes—sets up the rest of the data, decisions, and AI concentration
  - Recommended workflow: after learning Python & linear algebra.
  - Prereqs and why: linear algebra, probability, data structures, and discrete math; all necessary to understand optimal ways to clean & analyze data.
- **ORIE 4740 - Statistical Data Mining I**
  - What you'll learn: provides statistical foundation of data mining; including regression and Bayesian models.
  - Essential? Yes, for rigor. Pairs well with ORIE 3741.
  - Recommended workflow: after statistics & linear algebra, take before more specialized courses like RL.
  - Prereqs and why: statistics and probability, programming experience (Python); assignments are mostly statistical computation.
- **ORIE 4570 - Reinforcement Learning with Operations Research Applications**
  - What you'll learn: practical reinforcement learning algorithms (TD, gradient-descent, etc.) for decision-making in real-world problems
  - Essential? Probably not. Helpful if you're interested in research.
  - Recommended workflow: after optimization and probability/stats. Counts for ORIE elective.
  - Prereqs and why: ORIE 3300 (optimization) and ORIE 3500 (probability and statistics), need understanding of value-to-go functions and Markov Decision Processes. ORIE 3510 (Stochastic Processes) is also helpful, though not an explicit pre-requisite.
- **ORIE 4750 - Foundations of Causal Inference for Data-Driven Decisions (first offered AY 2026-2027)**
  - What you'll learn: how to move from correlation-based prediction to causal questions: counterfactuals, DAGs, etc.
  - Essential? No, but recommended if you're interested in product decisions & policy
  - Recommended workflow: After core stats and ML
  - Prereqs and why: strong probability and statistics, comfort with regresion and ML to understand assumptions and biases in causal models