# iQuHack 2025: Alice & Bob Challenge

> **Event:** [MIT iQuHACK 2025](https://www.iquack.io/) -- January 31 - February 2, 2025
> **Challenge:** [Alice & Bob -- Cat Qubit Simulation](https://github.com/iQuHACK/2025-Alice-and-Bob)
> **Team:** VeggieGalaxy

Simulating and controlling cat qubits in open quantum systems using two-photon
dissipation, Hamiltonian engineering, and optimal control with the `dynamiqs`
library and JAX.

## Features

- **Cat Qubit Stabilization (Challenge 1):** Simulate a cat qubit stabilized
  by two-photon dissipation, build composite Hilbert spaces, and analyze
  quantum state evolution.
- **Zeno Gate & Optimal Control (Challenge 1):** Implement a Zeno gate and
  use gradient-based optimal control (JAX + Adam) for state preparation.
- **Lab Frame Simulation (Challenge 2):** Model quantum systems in the lab
  frame with time-dependent Hamiltonians including SQUID and drive terms.
- **Visualization:** Wigner function animations, photon number evolution,
  parity tracking, and fidelity comparisons.

## Project Structure

```
iQuHack-2025/
├── Challenge 1.ipynb          # Tasks 1.1-1.4: cat qubit, adiabatic elimination, Zeno gate, optimal control
├── Challenge 2.ipynb          # Task 2.1: lab frame simulation (Task 2.2 incomplete)
├── submission/VeggieGalaxy/   # Hackathon submission copies
├── requirements.txt
├── .gitignore
└── README.md
```

## How to Use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Valmohaugen/iQuHack-2025.git
   cd iQuHack-2025
   ```

2. **Set up the environment:**
   ```bash
   conda create -n iquhack25 python=3.12
   conda activate iquhack25
   pip install -r requirements.txt
   ```

3. **Run the notebooks:**
   Open `Challenge 1.ipynb` and `Challenge 2.ipynb` in Jupyter or VS Code.

4. **Resources:**
   The [Alice & Bob challenge repo](https://github.com/iQuHACK/2025-Alice-and-Bob)
   contains background reading and reference materials.

## Results

- Stabilized cat qubit simulation with photon number, parity, and Wigner
  function evolution (Tasks 1.1-1.2)
- Fidelity comparison between full two-mode and adiabatically eliminated
  single-mode simulations across buffer dissipation rates (Task 1.2)
- Zeno gate implementation under two-photon dissipation (Task 1.3)
- Gradient-based optimal control for cat state preparation (Task 1.4)
- Lab frame Hamiltonian engineering with realistic SQUID parameters (Task 2.1)

**Note:** Task 2.2 (rotated-displaced frame simulation) was not completed
during the hackathon.
