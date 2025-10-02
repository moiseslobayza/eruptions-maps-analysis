# Volcano Eruptions — EDA & Interactive Maps 🌋

![Mapa interactivo (muestra)](reports/figures/hero_map.png)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/moiseslobayza/eruptions-maps-analysis/blob/main/notebooks/eruptions_maps_analysis.ipynb)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Made with: Python](https://img.shields.io/badge/Made%20with-Python-blue?logo=python)

---

## Overview
Exploratory analysis of global volcanic eruptions with interactive maps and basic EDA.  
Focus on data cleaning, VEI bucketing, decade grouping, and visualization (global map).

## Dataset
- **Source:** _[link a la fuente]_  
- **Key fields:** `volcano, latitude, longitude, year, country, type, vei`  
- **Sample:** `data/sample.csv` (~50 rows) included for testing.

## Methodology
1. Data cleaning: missing values, duplicates, type casting.  
2. Feature engineering: decade column, VEI bins.  
3. Visualization: interactive global map (Plotly/pydeck).

## Results (demo)
- Highest activity around the Pacific **Ring of Fire**.  
- Peak decades (e.g., **1950–1970**).  
- VEI distribution concentrated in **[2–3]**.

## Tech Stack
Python (pandas, numpy), matplotlib/plotly, folium/pydeck, Jupyter/Colab.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/eruptions_maps_analysis.ipynb


## 📂 Deliverables
- `notebooks/eruptions_map.ipynb` — full notebook with step-by-step analysis
- `notebooks/eruptions_map.html` — static HTML export (view without execution)
- `reports/figures/` — key figures (map, heatmap, bar charts)
- `data/sample.csv` — small demo dataset

## 📜 License
MIT License — This project is for educational and portfolio purposes.

