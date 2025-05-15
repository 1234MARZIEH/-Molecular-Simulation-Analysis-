# Molecular Dynamics Analysis Toolkit

This repository provides a Python-based analysis toolkit for processing Molecular Dynamics (MD) simulation trajectories. It uses the [MDAnalysis](https://www.mdanalysis.org/) library to compute:

- RMSD
- Radius of Gyration
- Hydrogen Bonds
- Solvent Accessible Surface Area (SASA)
- RMSF

## 📦 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

## ▶️ Usage

Put your topology (`.pdb`) and trajectory (`.xtc`) files in the `data/` folder and run:

```bash
python main.py
```

Plots and results will be saved in the `results/` folder.

## 📂 Example Data

For test runs, you can use small test files in `example_data/`, or download test datasets from [MDAnalysis Test Data](https://www.mdanalysis.org/pages/installation_quick_start/#test-files).

## 🧪 Testing with GitHub Actions

This repository uses GitHub Actions to ensure the toolkit runs on every commit.
