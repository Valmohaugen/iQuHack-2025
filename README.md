
# iQuHACK-2025: Alice & Bob Quantum Challenge

<<<<<<< HEAD
This repository contains all materials for the Alice & Bob challenge from iQuHack 2025, MIT's annual quantum computing hackathon.
=======
## Project Features

- **Challenge 1: Cat Qubit Stabilization and Analysis**
  - Simulates a cat qubit stabilized by two-photon dissipation.
  - Constructs composite Hilbert spaces, operators, and Hamiltonians.
  - Solves the Lindblad master equation for open quantum systems.
  - Visualizes quantum state evolution with Wigner functions and expectation values.
  - Compares full two-mode simulations with adiabatic elimination.
  - Implements a Zeno gate and optimal control for state preparation.
>>>>>>> f40f88b (updated README.md)

- **Challenge 2: Lab Frame Simulation and Hamiltonian Engineering**
  - Models a quantum system in the lab frame with time-dependent Hamiltonians.
  - Engineers Hamiltonians including asymmetrically threaded SQUID and one-photon drive.
  - Simulates system evolution and visualizes results.
  - Begins exploration of rotated-displaced frames.

- **Resources**
  - Provides links and references for background reading and example code.

- **Submission System**
  - Organized structure for team submissions, including sample solutions and documentation.

## Project Pipeline

1. **Setup and Exploration**: Start by exploring the main challenge notebooks, which guide you through quantum system setup, simulation, and analysis.
2. **Simulation**: Use Python and the `dynamiqs` library to construct operators, Hamiltonians, and solve the Lindblad master equation for open quantum systems.
3. **Visualization**: Generate plots and animations (e.g., Wigner functions, expectation values) to interpret quantum state evolution.
4. **Analysis and Engineering**: Compare different simulation approaches, implement gates, and apply optimal control techniques.
5. **Submission**: Organize your solutions and documentation in the provided submission structure for evaluation.

<<<<<<< HEAD
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
=======
## How to Use
>>>>>>> f40f88b (updated README.md)

1. **Clone the repository:**
	```bash
	git clone https://github.com/Valmohaugen/iQuHack-2025.git
	cd iQuHack-2025
	```

2. **Open the challenge notebooks:**
	- Use Jupyter Notebook or VS Code to open `Challenge 1.ipynb` and `Challenge 2.ipynb`.
	- Follow the step-by-step instructions in each notebook to complete the tasks.

3. **Consult Resources:**
	- Review the `Resources` file for background information and helpful links.

<<<<<<< HEAD
## Technical Notes

- All notebooks are expected to run in a standard Python environment with Jupyter support.
- Use the Resources directory for any helper scripts or data files.
=======
4. **Review and Submit Solutions:**
	- Check the `submission/VeggieGalaxy/` folder for a sample team submission.
	- Create your own team folder under `submission/` and add your completed notebooks and a README describing your approach and results.

5. **Dependencies:**
	- Ensure you have Python, Jupyter, and required packages (e.g., `dynamiqs`, `jax`, `matplotlib`, `numpy`, `scipy`) installed.
	- If additional packages are needed, list them in your team README or provide a `requirements.txt`.

## Results

When the project is run end-to-end:
- **Challenge 1** produces time-evolved quantum states of a cat qubit, with visualizations of photon number, parity, and Wigner functions. It demonstrates stabilization via two-photon dissipation, compares simulation methods, and shows the effect of quantum gates and optimal control.
- **Challenge 2** simulates the system in the lab frame, engineering complex Hamiltonians and visualizing the resulting quantum state evolution. The results include animations of the Wigner function and insights into Hamiltonian engineering.
- **Team Submissions** (e.g., VeggieGalaxy) provide example solutions, demonstrating successful implementation and analysis of the challenges.
>>>>>>> f40f88b (updated README.md)
