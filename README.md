# Hi, I'm Pedro Griff Marcincowski 👋
**Software Engineer | Financial Computing & Distributed Systems**  
*People Operations & Compensation Modeling @ Google $\rightarrow$ Software Engineering*

[![GitHub](https://img.shields.io/badge/GitHub-pedrogriff-181717?style=flat&logo=github)](https://github.com/pedrogriff)
[![Python](https://img.shields.io/badge/Python-3.11%20%7C%203.12%20%7C%203.13-blue?style=flat&logo=python)](https://python.org)
[![Code Style](https://img.shields.io/badge/Code%20Style-Ruff-000000?style=flat&logo=ruff)](https://github.com/astral-sh/ruff)
[![Type Checked](https://img.shields.io/badge/Type%20Checked-MyPy%20Strict-brightgreen)](https://mypy-lang.org)

---

### 🚀 Featured Engineering Systems

| Repository | Description & Highlights | Tech Stack | Status |
| :--- | :--- | :--- | :--- |
| **[`vesting-sim-engine`](https://github.com/pedrogriff/vesting-sim-engine)** | High-throughput Monte Carlo simulation & equity valuation engine. Distributes 48-month Google vesting tranches using the **Largest Remainder Method** to guarantee exact share conservation ($\sum s_i \equiv S_{\text{total}}$). Evaluates 19M+ price path steps in parallel via worker pools. | Python 3.13, Multiprocessing, Hypothesis, GBM Stochastic Modeling | [![CI](https://github.com/pedrogriff/vesting-sim-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/pedrogriff/vesting-sim-engine/actions) |
| **[`algocore-ds`](https://github.com/pedrogriff/algocore-ds)** | Production-grade laboratory for Computer Science data structures & memory profiling. Implements custom contiguous memory dynamic arrays, circular ring buffers (ArrayDeque), open-addressing HashMaps with Tombstones, and augmented AVL trees with $O(\log N)$ percentiles. | Python 3.13, Ctypes Raw Memory, Pytest, Benchmarking | [![CI](https://github.com/pedrogriff/algocore-ds/actions/workflows/ci.yml/badge.svg)](https://github.com/pedrogriff/algocore-ds/actions) |

---

### 🛠️ Technical Toolkit

* **Languages**: Python (Strict Typing, PEP 695 Generics, Modern Idiomatic), Java (Backend Exploration)
* **Engineering Craft**: Test-Driven Development (TDD), Property-Based Verification (`Hypothesis`), CI/CD (`GitHub Actions`), Linter Automation (`Ruff`, `MyPy Strict`)
* **Systems & Architecture**: Domain-Driven Design (DDD), Parallel Concurrency (`ProcessPoolExecutor`), Memory Models (CPU Spatial Locality, Cache Lines, Amortized Analysis)
* **Domain Strengths**: Total Rewards Analytics, Equity Vesting Mechanics (GSUs/PSUs), Financial Risk Modeling, Discrete Optimization

---

### 🏛️ Engineering Philosophy
1. **Mathematical Correctness**: Financial calculations must have provable invariants and zero rounding drift.
2. **Zero "Black Boxes"**: Deep understanding of how algorithms interact with CPU cache hierarchies, memory allocators, and operating system threads.
3. **Google Code Health**: Strict typing, modular boundaries, readable self-documenting code, and comprehensive test coverage (>90%).

---
*Open to discussions on distributed systems, compensation modeling, and high-performance backend engineering.*
