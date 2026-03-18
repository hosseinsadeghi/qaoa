# QAOA - Quantum Approximate Optimization Algorithm

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hosseinsadeghi/qaoa/blob/main/qaoa_tutorial.ipynb)

## Overview

The Quantum Approximate Optimization Algorithm (QAOA) is a hybrid quantum-classical algorithm for solving combinatorial optimization problems, originally introduced by Farhi, Goldstone, and Gutmann. It works by alternating between a cost Hamiltonian (encoding the problem) and a mixer Hamiltonian (exploring the solution space), with variational parameters optimized by a classical optimizer. QAOA serves as an accessible entry point into quantum computing, allowing experimentation with quantum algorithms on practical optimization tasks.

## What the Tutorial Covers

The notebook `qaoa_tutorial.ipynb` provides a step-by-step walkthrough of QAOA applied to the **Maximum Independent Set (MIS)** problem:

- Formulating MIS as a QUBO (Quadratic Unconstrained Binary Optimization) problem
- Converting QUBO to the Ising Hamiltonian form
- Understanding tensor products and Pauli operator exponentials as quantum gates
- Building the QAOA circuit from scratch using Qiskit
- Running the algorithm on a simulator and optimizing parameters with COBYLA
- Analyzing measurement results and comparing against brute-force solutions
- Investigating how the number of QAOA layers affects success rates

## Prerequisites

- Basic knowledge of quantum computing (qubits, gates, measurement)
- Python 3
- [Qiskit](https://qiskit.org/) and `qiskit-aer`
- NumPy, NetworkX, Matplotlib, SciPy

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
