# iQuHACK-2025

## Project Description

This repository contains all materials for the Alice & Bob challenge from iQuHACK 2025, a quantum computing hackathon. The challenge is designed to test participants' skills in quantum information, algorithm design, and collaborative problem solving. The project is organized to facilitate both individual exploration and team submissions.


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

### Hackathon Structure

Teams or individuals work on the provided notebooks, using the Resources directory for reference material. Submissions are organized by team name under the `submission/` directory. Each team should provide their completed notebooks and a README explaining their methods and results.

## Directory Layout

```
iQuHack-2025/
├── Challenge 1.ipynb         # Main challenge notebook 1
├── Challenge 2.ipynb         # Main challenge notebook 2
├── README.md                 # Project documentation
├── Resources/                # Reference materials, datasets, or helper scripts
└── submission/
	 └── VeggieGalaxy/
		  ├── Challenge 1.ipynb # Team VeggieGalaxy's solution to challenge 1
		  ├── Challenge 2.ipynb # Team VeggieGalaxy's solution to challenge 2
		  └── README.md         # Team-specific documentation
```

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

4. **Review Submissions:**
	- Check `submission/VeggieGalaxy/` for a sample team submission. Each team should create a similar folder structure.

## Submission Guidelines

- Create a folder under `submission/` with your team name.
- Add your completed challenge notebooks and a README describing your approach, results, and any technical notes.
- Ensure your code is well-documented and reproducible.

## Technical Notes

- All notebooks are expected to run in a standard Python environment with Jupyter support.
- If additional packages are required, list them in your team README or provide a requirements.txt.
- Use the Resources directory for any helper scripts or data files.

## License & Attribution

Refer to the hackathon guidelines for licensing. If you use external code or resources, provide proper attribution in your README or notebook.

## Contact & Issues

For questions, open an issue in the repository. For hackathon-specific inquiries, contact the organizers.
