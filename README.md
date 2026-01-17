# Difference‑in‑Differences Estimation (R)

## Overview
This repository contains scripts and documentation to replicate difference‑in‑differences (DiD) estimates, as demonstrated in Julia de Rom‑mont’s 2024 lecture. DiD is a causal inference method used to estimate treatment effects when randomization is not feasible.

## Contents
- `data/` – Example panel dataset with treatment and control groups.
- `analysis.R` – R script implementing DiD using the `did` package.
- `notebook.ipynb` – Walkthrough of the analysis in an interactive notebook.
- `figures/` – Plots illustrating parallel trends and treatment effects.

## Reproducing the Analysis
1. Install R and the required packages listed in `DESCRIPTION`.
2. Run `analysis.R` to process the data and estimate treatment effects.
3. View the resulting plots in the `figures/` directory.

## References
For a deeper understanding of the DiD methodology, see Callaway & Sant’Anna (2021). A link to the paper is provided in `references.md`.

## License
This project is licensed under the MIT License.
