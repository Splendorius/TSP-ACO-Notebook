# TSP-ACO-Notebook

Jupyter notebooks that implement **Ant Colony Optimization (ACO)** to solve the **Traveling Salesman Problem (TSP)**.  
Includes runnable experiments, basic visualizations, and parameter tuning to study convergence and solution quality.

---

## Features
- 🐜 ACO solver for TSP (pheromone trails, evaporation, heuristic visibility)
- ⚙️ Parameter tuning (α, β, ρ, number of ants, iterations)
- 📈 Plots for best/average tour length vs. iterations
- 🗺️ Simple route visualization for found tours

---

## Tech Stack
- **Python** (3.9+ recommended)
- **Jupyter Notebook**

---

Algorithm Overview (brief)

Each ant constructs a tour using probabilities weighted by:

Pheromone intensity (τ) with exponent α

Heuristic visibility (1/distance) with exponent β

After tours are built:

Pheromone evaporation with rate ρ

Pheromone deposit on edges from good tours

Iterate until the max iterations or convergence.

Key parameters to try:

alpha (α): pheromone importance (e.g., 1–2)

beta (β): heuristic importance (e.g., 3–6)

rho (ρ): evaporation rate (e.g., 0.1–0.5)

ants: number of ants (≈ number of cities or a multiple)

iterations: total optimization steps

## RUN

Launch Jupyter and Open     TSP-ACO-Notebook/PKatolik.ipynb, run cells top-to-bottom.
