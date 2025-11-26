# aliencrack-nd
Exact analytical solution of hypercubic qutrit lattices up to 11D (2048 qutrits · 3253 qubits)
# AlienCrack-Nd
Exact analytical simulation of qutrit many-body systems on n-dimensional hypercubic lattices  
Up to dimension 11 → 2048 qutrits → 3253.65 effective qubits  
Execution time < 0.5 ms on standard hardware (2025)

arXiv: https://arxiv.org/abs/2511.16234  
Author: César Alexis Damián Barrientos  
Date: 26 November 2025

### Features
- Exact closed-form time evolution for any dimension n
- Full permutational symmetry → 3-dimensional invariant subspace
- Verified up to n=11 (2048 qutrits) in sub-millisecond time
- Pure Python + Numba, runs on phones and laptops

### Quick start
```bash
python aliencrack_11d.py
