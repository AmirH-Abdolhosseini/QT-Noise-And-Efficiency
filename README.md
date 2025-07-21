# Quantum Teleportation Protocol Simulations

This repository accompanies the review paper (2025). It includes Python/Qiskit notebooks simulating teleportation under various entanglement structures and quantum noise channels.

##  Overview

This repository provides simulation code for analyzing the fidelity of quantum teleportation protocols under various quantum noise models. The work is implemented using **Qiskit** and focuses on evaluating protocol robustness against:

- Amplitude Damping
- Phase Damping
- Bit Flip Noise

The results support theoretical discussions in the main review paper and are reproducible with IBM's Qiskit simulation backend.


## Contents

- `2Qubit_QT_Fidelity_Noise.ipynb`: Simulates fidelity of standard quantum teleportation under amplitude, phase, and depolarizing noise using IBM Qiskit.
- Implements the standard quantum teleportation circuit
- Applies each noise channel separately
- Computes teleportation fidelity as a function of noise probability
- Generates comparative plots for noise robustness

## Dependencies
- Python 3.9+
- Qiskit >= 1.0
- matplotlib, numpy

To run the notebooks, install the following:

```bash
pip install qiskit matplotlib numpy
