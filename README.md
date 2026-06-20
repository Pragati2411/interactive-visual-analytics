# 🚀 SpaceX Falcon 9 — Launch Site Proximity Analysis with Folium

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Folium](https://img.shields.io/badge/Folium-Geospatial%20Maps-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview

This project uses **Folium** to build an interactive map of SpaceX Falcon 9 launch sites, exploring how launch outcomes and site location relate to nearby coastlines, cities, railways, and highways.

---

## 🎯 Objectives

- Mark all SpaceX launch sites on an interactive map using Folium
- Use colour-coded marker clusters to distinguish successful vs. failed landings at each site
- Add a live mouse-position tool to read map coordinates while exploring
- Calculate and visualise distances from each launch site to its nearest coastline, city, railway, and highway

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data loading and manipulation |
| Folium | Interactive geospatial mapping |
| Jupyter Notebook | Interactive analysis environment |

---

## 🔍 Key Features & Findings

### 🗺️ Launch Site Map
- Plotted all 4 Falcon 9 launch sites (CCAFS LC-40, CCAFS SLC-40, KSC LC-39A, VAFB SLC-4E) with circle markers and text labels

### 🟢🔴 Success/Failure Marker Clusters
- Added every individual launch record to the map using `MarkerCluster`, color-coded green for success and red for failure, making it easy to visually compare site performance

### 📍 Live Coordinate Tool
- Added the `MousePosition` plugin so coordinates can be read directly off the map while exploring

### 📏 Proximity Analysis
- Calculated real distances (Haversine formula) from launch sites to the nearest coastline, city, railway, and highway, and drew connecting lines on the map
- **Findings:** launch sites are **not** in close proximity to railways or highways, but **are** in close proximity to the coastline — consistent with safety-distance siting away from populated areas

---

## 📁 Project Structure

```
spacex-interactive-analytics/
├── Interactive Visual Analytics.ipynb   # Folium launch site & proximity analysis
└── README.md                             # Project documentation (this file)
```

---

## ▶️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Pragati2411/spacex-interactive-analytics.git
   cd spacex-interactive-analytics
   ```

2. **Install dependencies**
   ```bash
   pip install pandas folium wget jupyter
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook "Interactive Visual Analytics.ipynb"
   ```

---

## 💡 Insights Summary

> Mapping SpaceX's launch sites shows a clear siting pattern: all four sites sit close to a coastline (useful for safe abort and recovery operations) while staying well away from railways and highways. Color-coded marker clusters make it easy to compare success rates across sites at a glance, without reading raw tables.

---

## 🔮 Possible Next Step

A Plotly Dash dashboard (filterable by site/payload, with success-rate pie charts) would be a natural extension of this analysis — not yet built.

---

## 🔗 Related Projects in This Series

| Project | Description |
|--------|-------------|
| space-falcon-eda | Initial EDA & data wrangling on SpaceX launch data |
| spacex-data-visualization | Visualisations & feature engineering on launch data |
| spacex-sql-analysis | SQL-based analysis of SpaceX launch data |
| loan-prediction-ml | Classification model using Scikit-learn |

---

## 👩‍💻 Author
**Pragati Mistry** — Data Analyst | MSc Mathematics | IBM Data Science Professional Certificate  
📍 Surat, India | Open to Remote & Relocating to Mumbai / Hyderabad / Bangalore  
🔗 [GitHub Profile](https://github.com/Pragati2411)
**Pragati** — Data Analyst | MSc Mathematics | IBM Data Science Professional Certificate
📍 Surat, India | Open to Remote & Relocating to Mumbai / Hyderabad / Bangalore
🔗 [GitHub Profile](https://github.com/Pragati2411)
