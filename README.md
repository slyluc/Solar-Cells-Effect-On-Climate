# Physics Climate Modeling: Will Solar Panels Contribute to Global Warming?

This repository contains the code and data for my first-year physics project, where I investigate the impact of solar panels on the Earth's climate. The project uses a simplified energy balance model to simulate ocean surface temperatures under different future greenhouse gas scenarios. It includes a numerical solution of differential equations using the 4th-order Runge-Kutta method as well as a Monte Carlo simulation to assess uncertainty.

## Overview

**Project Title:**  
*Bliver solceller en kilde til global opvarmning?* (Will solar panels be a source of global warming?)

**Objective:**  
To determine whether the deployment of solar panels (especially in desert regions) could significantly affect Earth’s energy balance and contribute to global warming.

**Key Methods:**
- **Energy Balance Model:** Sets up the differential equation governing ocean surface temperature based on incoming solar radiation and outgoing longwave radiation.
- **Runge-Kutta 4th-Order Method:** Used to numerically integrate the differential equation.
- **Monte Carlo Simulation:** Employed to propagate uncertainties from model parameters to the final temperature predictions.
- **Scenario Analysis:** Comparison of various socio-economic pathways (SSP) to evaluate different future CO₂ emission scenarios.

## Repository Structure

- **`data/`**  
  Contains raw and processed datasets used in the simulations.

- **`docs/`**  
  Includes the full project report PDF ([FirstYear2023_17.pdf](docs/FirstYear2023_17.pdf)) and any additional documentation.

- **`notebooks/`**  
  Contains Jupyter Notebook(s) (e.g., [OceanJordPLOTS-SSP1-5.ipynb](notebooks/OceanJordPLOTS-SSP1-5.ipynb)) with exploratory data analysis, simulation results, and figure generation.

- **`figures/`**  
  Contains figures and plots produced by the simulations.

- **`requirements.txt`**  
  Lists the Python libraries required to run the code (e.g., NumPy, SciPy, Matplotlib, Pandas).

- **`LICENSE`** and **`.gitignore`**  
  Standard files for licensing and ignoring unnecessary files in the repository.

## Getting Started

### Prerequisites

Ensure you have Python 3.7+ installed. It is recommended to use a virtual environment.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/slyluc/Solar-Cells-Effect-On-Climate.git
   cd Solar-Cells-Effect-On-Climate
