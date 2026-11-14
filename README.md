# Steiner Systems in Applications

**Author:** Petr Neudek  
**License:** [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/)

## Overview

This repository contains a comprehensive set of combinatorial datasets, construction algorithms, and practical application models based on **Steiner systems $S(t, k, v)$** and **Partition Numerorum ($PN$)**. The work introduces novel construction techniques (including the *Actus* operator and *Berger tables*), investigates invariant properties of symmetric pair systems (referred to as the *supersoric* property), and demonstrates practical implementations in **cryptography, error-correcting codes, network topologies, and statistical experimental design**.

---

## Repository Contents

The dataset is organized into three structured Excel workbooks (`.xlsx`):

### 1. `Steiner system 2,2,4 and 2,3,7.xlsx`
Focuses on the construction, decomposition, and invariant verification of $S(2,3,7)$ systems derived from base $S(2,2,4)$ structures:
* **Construction Methods:** Visual and algorithmic roadmaps for extending $2 \times 6$ matrices into $3 \times 7$ systems, alongside a direct generation method via base triples (`123`–`127`) and intersection graphs.
* **Mathematical Framework & Supersoric Property:** Formal derivation of invariant missing-triple calculations ($\sigma$-sum) and validation of the *"half the rows plus one"* reconstruction rule.
* **Databases & Decomposition:** Complete listing of all 30 distinct $S(2,3,7)$ systems, a reference database of 120 paired systems (source vs. A-pillar-reflex systems), and structural decompositions using *Partition Numerorum* $PN(7)$.
* **Applications & Identification:** Type 2 constructors for inter-system cross-referencing (applicable to logistics and cryptography), Berger table $BT(7)$ Hamiltonian cycle routing, 6/49 lottery covering designs, and a 7-step system identification algorithm.

### 2. `Steiner system 2,3,9 and 2,4,13.xlsx`
Explores large-scale combinatorial databases of $S(3,3,9)$ systems, their transformation into $S(2,4,13)$ and $S(2,9,81)$ structures, and octal/ternary coding models:
* **Interactive System Explorer:** Dynamic conversion of all **15,360 distinct $S(3,3,9)$ systems** into 7-block grids of $S(2,3,9)$ and $7 \times S(2,4,13)$ configurations via the *Actus* operator.
* **Applications of $S(2,4,13)$ & $S(2,9,81)$:** Practical frameworks for binary/ternary Hamming error-correcting codes, Balanced Incomplete Block Designs (BIBD) for medical and industrial testing, secret-sharing schemes, and IoT wireless sensor network key distribution (37-element expanded routing systems).
* **Octal & Ternary Extensions:** Derivation of $C(2,8)$ octal coding structures (28 pairs / 56 triples) and $S(2,9,81)$ constructions relevant to ternary logic ($3^4 = 81$).

### 3. `Steiner system 2,4,16 and 2,5,21.xlsx`
Examines base-16 combinatorial architectures and their role in symmetric/stream encryption and high-throughput network design:
* **Base-16 Systems & Permutations:** Structural analysis of $S(2,4,16)$, $S(3,4,16)$, and $S(4,4,16)$ configurations, factorial permutation indexing ($16!$), and canonical matrix transformations ($(4!)^5 = 7,962,624$ configurations per matrix).
* **Code Compression (*Supersoric* Principle):** Quantitative analysis of information reduction—reconstructing 20-row $S(2,4,16)$ systems from 11 rows (45% reduction) and 140-row $S(3,4,16)$ systems from 44 rows (68.6% reduction)—along with cryptographic security trade-offs.
* **Applications of $S(2,5,21)$:** Derivation of $7 \times S(2,5,21)$ systems (decimal and hexadecimal representations), XOR stream-cipher key scheduling, binary Golay code $G_{24}$ relations, and low-latency supercomputer network topologies.

---

## Key Concepts & Terminology

* **Supersoric Property:** A structural invariant in symmetric pair and $k$-tuple systems whereby providing at least $\lfloor \frac{r}{2} \rfloor + 1$ valid rows uniquely and invariantly determines all remaining rows in the system (not to be confused with the biological term *suprasoric*).
* **Actus Operator:** A constructive mapping technique used to extend lower-order base matrices into higher-order Steiner systems (e.g., $S(2,2,4) \to S(2,3,7)$ or $S(3,3,9) \to S(2,4,13)$).
* **Constructors:** Specialized combinatorial decompositions (often derived from *Partition Numerorum*) designed to build complex covering schemes, branching pointers, or cryptographic key schedules.

---

## Citation & License

If you use these datasets or methods in your research, please cite this repository (or the corresponding Zenodo DOI archive) and credit the author:

> **Neudek, P.** (2026). *Steiner Systems in Applications*. GitHub / Zenodo. Licensed under CC BY-SA 4.0.

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).
