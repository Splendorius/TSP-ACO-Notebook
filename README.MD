# TSP-ACO-Notebook

A Python implementation of the **Ant Colony Optimization (ACO)** algorithm for the **Traveling Salesman Problem (TSP)**.  
Includes a simple **Tkinter GUI** to adjust parameters, select datasets, and visualize the best tour.

---

## Features
- 🐜 ACO algorithm (pheromone trails, evaporation, heuristic visibility)
- 🎛️ Adjustable parameters:
  - Number of ants
  - α (pheromone influence)
  - β (heuristic influence)
  - ρ (pheromone evaporation rate)
  - Q (pheromone deposit factor)
  - Iterations
- 📂 Dataset selector for TSPLIB instances (`ulysses22.tsp`, `berlin52.tsp`, `eil101.tsp`)
- 📈 Live visualization of cities, best path, and best path length
- 🖥️ Tkinter-based GUI with Matplotlib plotting

---

## Tech Stack
- **Python** (3.9+ recommended)
- **Jupyter Notebook**
- **Tkinter** (standard library)
- **NumPy**, **Matplotlib**

---

## Run

1. Launch Jupyter Notebook  
2. Open:
```text
PKatolik.ipynb
```
3. Run the cells top-to-bottom
