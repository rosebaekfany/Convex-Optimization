# Convex Optimization — Semidefinite Relaxation

Code and report for the **Convex Optimization** course project.

---

## 📖 Project Overview

This project explores **convex optimization techniques**, focusing on the application of **Semidefinite Relaxation (SDR)** to classical non-convex problems. The report presents theoretical background, problem formulations, and algorithmic approaches.

---

## 🧩 Main Topics

1. **MIMO Detection**

   * Application of SDR to symbol detection in wireless communication systems.
   * Comparison of methods: Zero Forcing (ZF), MMSE, Sphere Decoding, SDR, and Lattice Reduction.
   * Trade-offs between detection accuracy and computational complexity.

2. **Max-Cut Problem**

   * A fundamental NP-hard problem in graph theory and combinatorial optimization.
   * Reformulation using adjacency and Laplacian matrices.
   * **SDP relaxation** approach and **Hyperplane Rounding Algorithm (Goemans–Williamson)** for approximation.

3. **Graph Coloring**

   * Problem setup: assigning colors so adjacent vertices differ.
   * SDP relaxation of the chromatic number.
   * Wigderson’s algorithm for 3-colorable graphs.
   * Advanced methods using the **Lovász number** and refined **Karger–Motwani–Sudan (KMS)** algorithm.

## 📂 Contents

| File | Description |
|---|---|
| `convex_project_report.pdf` | Project report |
| `project-mimo.ipynb` | MIMO detection: ZF, MMSE, sphere decoding and SDR |
| `MaxCut_GraphColoring (1).ipynb` | Max-Cut (Goemans–Williamson) and graph colouring with SDP relaxation |

## 📚 References

* Asratian, A. S., Denley, T. M. J., & Häggkvist, R. (1998). *Bipartite Graphs and Their Applications*. Cambridge University Press.
* Pucher, D., & Rendl, F. (2024). *Practical Experience with Stable Set and Coloring Relaxations*. [arXiv:2401.17069](https://arxiv.org/abs/2401.17069)

