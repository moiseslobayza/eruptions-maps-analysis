# Volcano Eruptions — EDA & Interactive Maps 🌋

## Overview
Exploratory analysis of global volcanic eruptions with interactive maps and basic EDA.  
Focus on data cleaning, VEI bucketing, decade grouping, and visualizations (global map, density heatmap, top countries/volcanoes).

## Dataset
- Source: [add link or description]
- Key fields: `volcano`, `latitude`, `longitude`, `year`, `country`, `type`, `vei`
- A small `data/sample.csv` (~50 rows) is included for testing.

## Methodology
1. **Data cleaning:** missing values, duplicates, type casting.
2. **Feature engineering:** decade column, VEI bins.
3. **Visualizations:**
   - 🌍 Interactive global map (Folium/PyDeck)
   - 🔥 Density heatmap
   - 📊 Bar charts: top countries/volcanoes by events/VEI

## Results (demo)
- Highest activity around the **Pacific Ring of Fire**.
- Peak decades: **[e.g., 1950–1970]**.
- VEI distribution concentrated in **[e.g., 2–3]**.

## Tech Stack
Python (pandas, numpy), matplotlib/plotly, folium/pydeck, Jupyter/Colab.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/eruptions_map.ipynb

## 📂 Deliverables
- `notebooks/eruptions_map.ipynb` — full notebook with step-by-step analysis
- `notebooks/eruptions_map.html` — static HTML export (view without execution)
- `reports/figures/` — key figures (map, heatmap, bar charts)
- `data/sample.csv` — small demo dataset

## 📜 License
MIT License — This project is for educational and portfolio purposes.

