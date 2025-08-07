# 🧠 Quantum Galton Box Simulator — Universal Statistical Simulator

This project implements a scalable **Quantum Galton Box (QGB)** using Qiskit, inspired by the paper *Universal Statistical Simulator* by Carney & Varcoe ([arXiv:2202.01735](https://arxiv.org/abs/2202.01735)).

The QGB acts as a **quantum Monte Carlo simulator**, evaluating all paths of a Galton board in quantum superposition to generate distributions such as:
- **Gaussian (binomial)**
- **Exponential**
- **Hadamard-based quantum walk**

This approach demonstrates how **quantum circuits can simulate complex high-dimensional systems**, a relevant method for particle transport, statistical physics, and quantum PDE solvers.

---

## 📁 Project Structure

```bash
quantum-galton-box/
├── README.md               # Project overview
├── requirements.txt        # Python dependencies
├── src/
│   └── qgb_circuit.py      # Circuit builder and simulator
├── notebooks/
│   └── qgb_simulation.ipynb# Interactive demo and plots
├── results/
│   └── *.png / *.csv       # Output histograms and metrics
└── docs/
    └── 2pager_summary.pdf  # Technical summary of the paper

