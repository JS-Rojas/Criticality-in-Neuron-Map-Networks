# Criticality in Neuron Map Networks

This repository contains the code to reproduce the figures and results from the article **"Chaotic Griffiths Phase in Neuron Map Networks"**.

Interactive version: https://js-rojas.github.io/Criticality-in-Neuron-Map-Networks/#model

## Usage

Each script generates one of the figures from the article. Before running a script, make sure to download the corresponding data files (`.csv`) into the same directory.

## Contents

- **Time series** — `WP_time_series.ipynb`
- **DFC measures** — `WP_DFC.ipynb` (uses `DFC-Heterogeneity-parameters.csv` for the Global Network and `DFC-Both-Heterogeneities.csv` for the Small World Network)
- **Cluster evolution in time** — `WP_Max_Clus_Evolution.ipynb`
- **Power-law generator** — `WP_PoweLaw_1.ipynb`
- **Maximum likelihood estimation of the scaling exponents** — `WP_PowerLawPlots.ipynb` (uses `griffiths_data.csv`, `griffiths_data_extra_eps.csv`, and `griffiths_data_extra_eps2.csv` for the Global Coupling Network, and `SWN_Heterogeneity_data.csv` and `SWN_Heterogeneity_data_extra_eps.csv` for the Small World Network)

## Citation

If you use this code, please cite the article:

> *Chaotic Griffiths Phase in Neuron Map Networks*

## Author

[JS-Rojas](https://github.com/JS-Rojas), Mario Cosenza
