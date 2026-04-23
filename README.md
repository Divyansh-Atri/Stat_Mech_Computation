# Statistical Mechanics Class Graph

This repository contains class-wise computational physics work (random walks, Ising model, and Lennard-Jones Monte Carlo simulation) organized by folder.

## Repository Structure

- `class1 `
  - `class1_combined.ipynb`: Combined notebook for 1D random-walk analyses.
  - `random_walk_statistics.png`: Output figure from random-walk statistics.
  - `meeting_probability.png`: Output figure for two-walker meeting probability.

- `class2`
  - `ising.ipynb`: 2D Ising model simulation using Metropolis updates, including:
    - energy vs accepted steps
    - magnetization analysis
    - susceptibility-related calculations

- `class3`
  - `file.ipynb`: Monte Carlo simulation of a Lennard-Jones fluid with periodic boundaries, including:
    - initialization with minimum-distance constraint
    - Metropolis particle moves
    - energy tracking
    - acceptance behavior
    - radial distribution style analysis

## Prerequisites

Use Python 3.10+ (or any modern Python 3 environment).

Install the core dependencies:

```bash
pip install numpy matplotlib scipy
```

## How to Run

Open the notebooks in VS Code (or Jupyter) and run cells in order.

1. `class1 /class1_combined.ipynb`
2. `class2/ising.ipynb`
3. `class3/file.ipynb`

Notes:
- The folder name `class1 ` contains a trailing space.
- Some notebooks include `%pip install ...` cells; if packages are already installed, you can skip them.

## Outputs

The notebooks generate plots and, in some cases, save image files such as:
- `class1 /random_walk_statistics.png`
- `class1 /meeting_probability.png`

## Topics Covered

- 1D random walks and ensemble observables
- Meeting probability of two random walkers with exact and asymptotic comparisons
- 2D Ising model under the Metropolis algorithm
- Lennard-Jones Monte Carlo simulation in periodic boundary conditions

## Suggested Workflow

- Use a dedicated virtual environment for reproducibility.
- Run notebook cells top-to-bottom to ensure variables are defined in order.
- If results differ after re-running, set/confirm random seeds in the parameter cells.
