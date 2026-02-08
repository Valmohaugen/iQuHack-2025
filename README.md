# iQuHACK-2025: Alice & Bob Quantum Challenge

This repository is the home for the iQuHACK 2025 Alice & Bob challenge, focused on simulating and controlling cat qubits in open quantum systems. 

## Features

- **Cat Qubit Stabilization & Analysis:** Simulate a cat qubit stabilized by two-photon dissipation, build composite Hilbert spaces, and analyze quantum state evolution using the `dynamiqs` library and JAX.
- **Lab Frame Simulation & Hamiltonian Engineering:** Model quantum systems in the lab frame, engineer time-dependent Hamiltonians (including SQUID and drive terms), and visualize results.
- **Open Quantum System Simulation:** Solve the Lindblad master equation, compare simulation approaches, and implement advanced gates and optimal control.
- **Visualization:** Generate plots and animations (Wigner functions, expectation values) to interpret quantum state evolution.
- **Team Submission System:** Organized structure for submitting solutions, with sample solutions provided.
- **Resources:** Reference materials and example code for background and support.

## Pippeline

Start by exploring the main challenge notebooks. You'll set up quantum systems, construct operators and Hamiltonians, and simulate their evolution. The workflow is interactive: run code, visualize results, and iterate on your approach. The project encourages experimentation—try different simulation methods, implement gates, or optimize state preparation. When ready, organize your work for submission using the provided structure.

## How to Use This Repository

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Valmohaugen/iQuHack-2025.git
   cd iQuHack-2025
   ```
2. **Open the challenge notebooks:**
   - Use Jupyter Notebook or VS Code to open `Challenge 1.ipynb` and `Challenge 2.ipynb`.
   - Follow the instructions in each notebook to complete the tasks and explore the physics.
3. **Consult Resources:**
   - The `Resources` file contains background reading and helpful links (e.g., [iQuHACK 2025 Alice & Bob](https://github.com/iQuHACK/2025-Alice-and-Bob)).
4. **Review and Submit Solutions:**
   - See the `submission/VeggieGalaxy` folder for a sample team submission.
   - Create your own team folder under `submission/` and add your completed notebooks and a README describing your approach and results.
5. **Dependencies:**
   - Make sure you have Python, Jupyter, and the required packages (`dynamiqs`, `jax`, `matplotlib`, `numpy`, `scipy`).
   - If you use additional packages, list them in your team README or provide a `requirements.txt`.

## Results

Running the project end-to-end, you will:

- Simulate and visualize the stabilization of a cat qubit, including photon number, parity, and Wigner function evolution.
- Engineer and analyze lab-frame Hamiltonians, producing animations and insights into quantum state dynamics.
- Compare simulation methods, implement gates, and apply optimal control.
- **Dependencies:**
   - Ensure you have Python, Jupyter, and required packages (e.g., `dynamiqs`, `jax`, `matplotlib`, `numpy`, `scipy`) installed.
