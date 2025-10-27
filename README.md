# Fractional Rheology of Methylcellulose Thermogelation (`fracMC`)

This repository contains the experimental data, analysis scripts, and figures supporting the manuscript:

> **Fractional Rheology of Methylcellulose Thermogelation**  
> *[Authors]* — 2025, *Manuscript under review*

All content in this repository is provided to ensure **transparency, reproducibility, and open access** to the data and computational workflow used in the study.

---

## Overview

This project investigates the **fractional viscoelastic behavior** of methylcellulose during thermogelation.  
Using rheological experiments and fractional-order modeling, we characterize the transition from viscous to elastic response with temperature.

The repository includes:

- Raw and processed rheological data  
- Jupyter notebooks for data analysis, model fitting, and figure generation  
- Python source code for the fractional models and fitting routines  
- Figures and numerical results corresponding to the manuscript and supplementary materials  

---

## Repository Structure

```
fracMC/
├── data/               
│   ├── raw/             # Original experimental data
│   └── processed/       # Cleaned and pre-processed datasets
│
├── notebooks/           # Jupyter notebooks for data analysis and visualization
│   ├── 01_preprocessing.ipynb
│   ├── 02_analysis.ipynb
│   ├── 03_model_fitting.ipynb
│   ├── 04_figures.ipynb
│
├── figures/
│   ├── main/            # Figures appearing in the main text
│   └── supplementary/   # Figures for the Supporting Information
│
├── results/             # Output files (parameters, tables, and summary data)
│   ├── model_parameters.csv
│   ├── summary_statistics.csv
│   └── sensitivity_analysis.csv
│
│
├── environment.yml      # Conda environment file for reproducibility
├── LICENSE
└── README.md
```

---

## Installation and Requirements

Create a reproducible environment with Conda:

```bash
conda env create -f environment.yml
conda activate fracMC
```

or install dependencies manually (Python ≥ 3.10):

```bash
pip install numpy pandas scipy matplotlib seaborn jupyterlab lmfit
```

---

## Usage Guide

1. **Clone the repository**
   ```bash
   git clone https://github.com/mirandi1/fracMC.git
   cd fracMC
   ```

2. **Launch JupyterLab**
   ```bash
   jupyter lab
   ```

3. **Execute the notebooks in sequence:**
   - `01_preprocessing.ipynb` – Clean and organize raw data  
   - `02_analysis.ipynb` – Analyze rheological trends  
   - `03_model_fitting.ipynb` – Fit fractional rheology models  
   - `04_figures.ipynb` – Generate figures for the manuscript  

All figures and processed outputs are automatically saved to `/figures` and `/results`.

---

## Data Description

- **`data/raw/`** — Original experimental rheology measurements, including temperature sweeps and frequency sweeps.  
- **`data/processed/`** — Curated datasets ready for analysis (unit-consistent and formatted).  

Each data file includes a header specifying experimental conditions and units.

---

## Figures and Results

All figures appearing in the paper are generated through the provided notebooks.  
Figures are stored in:

- `/figures/main/` — Figures used in the main text  
- `/figures/supplementary/` — Figures for the Supporting Information  

Key numerical outputs (fit parameters, model statistics) are stored in `/results/`.

---

## Citation

If you use or build upon this repository, please cite:

> **Fractional Rheology of Methylcellulose Thermogelation**  
> *[Authors]*, 2025. *Manuscript under review.*

A DOI and full citation will be provided once the paper is published.

---

## License

This repository and its contents are distributed under the [MIT License](LICENSE).  
You are free to use, modify, and redistribute this material with proper attribution.

---

## Contact

For questions, data requests, or collaborations, please contact:

**[Isaac Y. Miranda Valdez]**  
[Aalto University]  
[isaac.mirandavaldez@aalto.fi]
