# iQuHACK-2025

## Project Description

This repository contains all materials for the Alice & Bob challenge from iQuHack 2025, MIT's annual quantum computing hackathon. The challenge is designed to test participants' skills in quantum information, algorithm design, and collaborative problem solving. The project is organized to facilitate both individual exploration and team submissions.


### Challenge Descriptions

#### Challenge 1: Cat Qubit Stabilization and Analysis

This notebook simulates and analyzes a cat qubit stabilized by two-photon dissipation. Tasks include:

- Setting up composite Hilbert spaces for memory and buffer modes
- Constructing annihilation and creation operators
- Building a Hamiltonian with two-photon exchange and one-photon drive
- Initializing the system in the vacuum state
- Solving the Lindblad master equation for time evolution
- Calculating and plotting expectation values for photon number and parity in the memory mode
- Visualizing the Wigner function evolution
- Comparing full two-mode simulation with adiabatic elimination of the buffer mode and plotting fidelity
- Implementing a Zeno gate and analyzing its effect
- Applying optimal control to prepare a target cat state using gradient-based optimization

#### Challenge 2: Lab Frame Simulation and Hamiltonian Engineering

This notebook simulates a quantum system in the lab frame and engineers the Hamiltonian. Tasks include:

- Setting up Hilbert spaces for memory and buffer modes
- Defining physical constants for the system
- Constructing time-dependent Hamiltonians, including an asymmetrically threaded SQUID term and one-photon drive
- Initializing the system in the vacuum state
- Solving the Lindblad master equation for time evolution
- Visualizing the Wigner function for the memory mode
- Beginning simulation in a rotated-displaced frame

---

## How to Use This Repository

1. **Clone the repository:**
	```bash
	git clone https://github.com/Valmohaugen/iQuHack-2025.git
	cd iQuHack-2025
	```

2. **Open the challenge notebooks:**
	- Use Jupyter Notebook or VS Code to open `Challenge 1.ipynb` and `Challenge 2.ipynb`.
	- Follow instructions in each notebook to complete the tasks.

3. **Consult Resources:**
	- The `Resources` directory may contain background information, example code, or datasets relevant to the challenges.

## Technical Notes

- All notebooks are expected to run in a standard Python environment with Jupyter support.
- Use the Resources directory for any helper scripts or data files.
