---
layout: default
title: Financial Engineering Page
permalink: /oriemajor-fineng/
---
\
\
[Home]({{ '/' | relative_url }}) → [Operations Research & Engineering]({{ '/oriemajor/' | relative_url }}) → Financial Engineering

# ORIE Major - Financial Engineering
Field of study on quantitative analysis and management of financial instruments and risk.

## Flow Map
```mermaid
flowchart TD

  %% ===== PREREQS =====
  subgraph A1[Prerequisites]
    A1a[CS 1110/1112 Intro to Python]
    A1b[CS 2110 OO Programming]
    A1c[MATH 2210/2940 Linear Algebra]
    A1d[ENGRD 2700 or ORIE 3500 Probability & Stats]
  end

  %% ===== FOUNDATIONS =====
  subgraph B1[Foundations in Data & Optimization]
    B1a[ORIE 3320 Optimization for AI]
    B1b[ORIE 3741 Learning with Big Messy Data]
  end

  %% ===== CORE METHODS =====
  subgraph C1[Core ML & Inference]
    C1a[ORIE 4740 Statistical Data Mining I]
    C1b["ORIE 4750 Foundations of Causal Inference (AY 26–27)"]
  end

  %% ===== ADVANCED DECISION SYSTEMS =====
  subgraph D1[Advanced Intelligent Decision Systems]
    D1a[ORIE 4570 Reinforcement Learning with OR Applications]
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
- **ORIE 4350 - Introduction to Game Theory**
  - What you'll learn: broad survey of mathematical theory of games
  - Essential? No, but can help with understanding market microstructure & trading.
  - Recommended workflow: no strict time frame.
  - Prereqs and why: Optimization I, for basic linear programming (& algebra) knowledge.
- **ORIE 4600 - Introduction to Financial Engineering**
  - What you'll learn: important ideas in modern finance like arbitrage, pricing, derivatives, risk measures. Focuses on discrete time models.
  - Essential? Yes, provides a foundation for financial engineering concepts.
  - Recommended workflow: Take early, prereq for other financial engineering courses.
  - Prereqs and why: probability & statistics. Stochastic processes. Necessary for understanding the randomness and probabilistic nature of finance.
- **ORIE 4630 - OR Tools for Financial Engineering**
  - What you'll learn: applications of probability, stats, and optimization to finance. Time series, portfolio, pricing models.
  - Essential? Yes, covers important financial models & pricing techniques.
  - Recommended workflow: after ORIE 4600, though not an explicit pre requisite.
  - Prereqs and why: linear algebra, statistics and probability, and knowledge of R/multiple linear regression. R is widely used for computation & simulation in the course.
- **ORIE 4656 - Extreme Values in Finance**
  - What you'll learn: tail risk modeling, extremely value theory, and systemtic risk
  - Essential? Recommended if you're interested in risk analytics.
  - Recommended workflow: following a probability/stats foundation.
  - Prereqs and why: probability (tail distributions), core topic in course.
- **ORIE 5550 - Applied Time-Series Analysis**
  - What you'll learn: statistical tools for analysis of time-dependent data.
  - Essential? Yes, very useful in financial engineering jobs.
  - Recommended workflow: After an intro statistics / probability course. Graduate students get first priority.
  - Prereqs and why: stats and probability.
- **ORIE 5600 / 5610 - Financial Engineering with Stochastic Calculus I & II**
  - What you'll learn: continuous-time models and mathematical tools required to use them.
  - Essential? No, but covers a lot of important topics like Black-Scholes, Brownian Motion. Priority given to grad students.
  - Recommended workflow: After stochastic processes, with a strong probability foundation.
  - Prereqs and why: ORIE 3510, understanding of random proceeses.


