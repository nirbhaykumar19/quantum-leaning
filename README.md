# Quantum Computing with Qiskit

This repository contains hands-on Jupyter notebooks that introduce quantum computing through foundational concepts, measurements, and widely used quantum algorithms. The lessons use Qiskit to build and explore quantum circuits, with simulations and, where supported, quantum hardware demonstrations.

## Notebook Guide

### Getting Started with Qiskit
An introduction to the Qiskit workflow: create a quantum circuit, add gates and measurements, and run it with a simulator or an available backend. This notebook establishes the tools and circuit concepts used throughout the collection.

### Superposition
Explore how a qubit can be prepared in a superposition of computational-basis states. Build simple circuits and compare measurement outcomes with the probabilities predicted by the quantum state.

### Stern–Gerlach Measurements
Study spin measurements and the role of measurement basis. The notebook uses the Stern–Gerlach experiment as a model for understanding how measuring a quantum system along different axes changes the outcomes and what can be learned about its state.

### Exploring Uncertainty
Investigate uncertainty in quantum measurements, especially for observables that cannot be precisely known at the same time. Circuit experiments connect measurement statistics to the uncertainty principle.

### Deutsch–Jozsa Algorithm
Learn how a quantum algorithm can identify whether a promised Boolean function is constant or balanced. The circuit uses an oracle and quantum interference to solve the problem with a single query under the algorithm's assumptions.

### Grover's Search Algorithm
Explore quantum search for a marked item in an unstructured set. Grover's algorithm uses an oracle and amplitude amplification to increase the probability of measuring the desired answer.

### Quantum Fourier Transform
Study the quantum counterpart of the discrete Fourier transform. The QFT maps phase and periodic structure into a form useful to other quantum algorithms, including phase estimation and Shor's algorithm.

### Shor's Algorithm
Examine how quantum period finding can be used for integer factorization. The notebook introduces the algorithm's main stages and the role of the QFT, illustrating why large-scale fault-tolerant quantum computers could affect some public-key cryptography.

### Bell's Inequality
Use entangled qubits to investigate correlations between measurements. The notebook compares quantum predictions with the bounds imposed by Bell inequalities on local hidden-variable theories.

### Quantum Key Distribution
Explore the BB84-style approach to sharing a secret key using quantum states. Random preparation and measurement bases let communicating parties form a shared key and detect evidence of interception.

### Quantum Teleportation
Build a circuit that transfers an unknown qubit state using shared entanglement and classical communication. The protocol transfers quantum state information, not matter, and its measurement steps show how the original state is reconstructed remotely.

### Variational Quantum Eigensolver (VQE)
Explore a hybrid quantum-classical method for estimating a system's ground-state energy. A parameterized circuit prepares trial states while a classical optimizer adjusts its parameters to reduce the measured energy.

## Getting Started

- Install Jupyter and the Qiskit packages required by the notebook you plan to run. Each notebook lists its own dependencies and setup notes.
- Open a notebook in JupyterLab or Visual Studio Code and run its cells in order.
- Many lessons can be explored with simulators. Running jobs on IBM quantum hardware requires an appropriately configured IBM Quantum account and access to a supported backend.
- Some exercises use `qc-grader` for progress checks or answer validation. Follow the grader and package instructions in the relevant notebook; grading helpers may depend on a specific course package version.

## Learning Path

For a gentle progression, start with **Getting Started with Qiskit**, **Superposition**, **Stern–Gerlach Measurements**, and **Exploring Uncertainty**. Then explore the algorithms and applications: **Deutsch–Jozsa**, **Grover's Search**, **Quantum Fourier Transform**, **Shor's Algorithm**, **Bell's Inequality**, **Quantum Key Distribution**, **Quantum Teleportation**, and **VQE**.
