# SevenFold  
### A Deterministic Geometric Proof of Consensus  

**SevenFold** introduces a new class of deterministic consensus: one that converges through **geometric structure rather than probability, randomness, timing assumptions, or leader election**.

This work demonstrates that bounded deterministic agreement is achievable without entropy-based mechanisms, addressing limitations long assumed by classical consensus theory.

SevenFold is presented as a **Proof of Consensus (PoC)** — a geometric decision engine that produces agreement through structure, symmetry breaking, and bounded evaluation rather than stochastic processes.

---

## Canonical Publication

The authoritative, citable version of this work is published on Zenodo:

https://doi.org/10.5281/zenodo.17914272

---

## What Problem This Solves  

For decades, distributed systems have relied on probabilistic techniques to overcome the impossibility of deterministic agreement under contention. As a result, modern consensus systems depend on randomness, stake weighting, leader selection, or timing assumptions.

SevenFold shows that these assumptions are not strictly necessary.

By modeling consensus as a **geometric convergence problem**, SevenFold demonstrates that agreement can be reached deterministically in a bounded number of steps — without relying on probability or trust-weighted influence.

---

## What SevenFold Is  

SevenFold models consensus as a geometric process composed of:

- Independent participant inputs (“winds”)
- A convex centroid representing collective agreement
- A deterministic harmonic rotor defined over a finite cyclic group
- A bounded lawfulness evaluator (“governing disk”)

Together, these components form a deterministic decision engine that converges in a guaranteed maximum number of rotor cycles.

This approach reframes consensus as **geometry plus structure**, rather than voting, randomness, or leader control.

---

## What This Repository Represents  

This repository serves as:

- A public record of discovery and attribution  
- A reference implementation of the SevenFold consensus model  
- A conceptual foundation for deterministic geometric consensus  

It is **not** a production-ready implementation, nor does it grant unrestricted rights to commercial use.

Detailed optimizations, scaling strategies, and production integrations are intentionally outside the scope of this repository.

---

## Intellectual Property & Licensing  

SevenFold is **patent-pending** (provisional filed December 1, 2025).

This work is released under a  
**Creative Commons Attribution–NonCommercial–NoDerivatives 4.0 International (CC BY-NC-ND 4.0)** license.

You are free to:
- Read, study, and cite this work
- Share the material with attribution

You may **not**:
- Use this work for commercial purposes
- Create derivative implementations
- Deploy or integrate SevenFold into production systems without permission

Commercial licensing, collaborations, and authorized implementations are managed by **SevenFold Labs LLC**.

---

## Attribution  

**Inventor & Author**  
Adrian John Weddington  
SevenFold Labs LLC  

---

## Status  

- Zenodo archival record published  
- Patent pending  
- Reference implementation in active development  

---

## Contact  

For licensing inquiries, research collaboration, or authorized implementations:

**SevenFold Labs LLC**  
📧 SevenFoldLabs@gmail.com

---

## Intellectual Property Notice

SevenFold is a patent-pending deterministic consensus protocol.
All rights are reserved by SevenFold Labs LLC.

This repository is published for research, review, and citation purposes only.
Commercial use or derivative works require explicit written permission.
