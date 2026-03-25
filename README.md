# DOE Project: Plackett-Burman Screening for Adaptive Winglet Design

This repository contains a reproducible Design of Experiments (DOE) workflow focused on a 12-run Plackett-Burman screening study for winglet geometry factors and drag coefficient response.

The main notebook reconstructs and explains:

- factor contrasts and main effects,
- ANOVA decomposition (Model, Error, Total),
- factor-level significance using F-tests and right-tail p-values,
- Pareto-style standardized effect visualization,
- reduced-model selection by removing the least significant factor.

## Main notebook

- Notebook: `content/pb_screening_anova_demo.ipynb`

## Repository structure

- `content/`: notebook content served by JupyterLite
- `repl/`: JupyterLite configuration
- `requirements.txt`: Python package requirements for compatibility/reproducibility

## How to run

### Option A: Open in JupyterLite (browser)

The notebook can be opened directly in the browser through the published JupyterLite site.

### Option B: Run locally in VS Code/Jupyter

1. Open the repository.
2. Install dependencies from `requirements.txt`.
3. Open `content/pb_screening_anova_demo.ipynb` and run cells top-to-bottom.

