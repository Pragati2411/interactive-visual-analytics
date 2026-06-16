# 🚀 SpaceX Falcon 9 — Interactive Visual Analytics

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Folium](https://img.shields.io/badge/Folium-Geospatial%20Maps-green)
![Plotly Dash](https://img.shields.io/badge/Plotly%20Dash-Interactive%20Dashboard-purple?logo=plotly)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview

This project builds **interactive visualisations** of the SpaceX Falcon 9 launch dataset using **Folium** for geospatial mapping and **Plotly Dash** for a web-based interactive dashboard. The goal is to let users explore launch sites, proximity factors, and success patterns visually and interactively, rather than through static charts alone.

> Note: this README is based on the standard IBM Data Science Capstone curriculum for this notebook. If your specific notebook covers slightly different content, feel free to adjust the sections below to match exactly what you built.

---

## 🎯 Objectives

- Mark all SpaceX launch sites on an interactive map using Folium
- Use colour-coded markers/clusters to distinguish successful vs failed landings at each site
- Calculate and visualise distances from launch sites to nearby coastlines, highways, railways, and cities
- Build an interactive Plotly Dash dashboard to filter and explore launch outcomes by site, payload, and year

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data loading and manipulation |
| Folium | Interactive geospatial mapping |
| Plotly Dash | Web-based interactive dashboard |
| Jupyter Notebook | Interactive analysis environment |

---

## 🔍 Key Features

### 🗺️ Folium Interactive Map
- All Falcon 9 launch sites plotted on a world map with circle markers and site labels
- Marker clusters used to show launch outcomes (success/failure) at each site with color-coded icons
- `MousePosition` plugin added to display real-time coordinates while exploring the map
- Distance lines drawn from launch sites to the nearest coastline, city, railway, and highway to analyse site selection criteria (e.g., safety distance from populated areas)

### 📊 Plotly Dash Dashboard
- Dropdown menu to filter launches by site (or view all sites)
- Pie chart showing the proportion of successful vs failed launches for the selected site
- Range slider to filter by payload mass
- Scatter plot showing the relationship between payload mass and launch success, colour-coded by booster version

---

## 📁 Project Structure

```
spacex-interactive-analytics/
├── Interactive Visual Analytics.ipynb   # Folium maps & Plotly Dash dashboard
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
   pip install pandas folium plotly dash jupyter
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook "Interactive Visual Analytics.ipynb"
   ```

---

## 💡 Insights Summary

> Interactive mapping reveals that SpaceX launch sites are deliberately positioned at a safe distance from major cities and railways, while remaining close to coastlines to support safe abort and recovery operations. The Plotly Dash dashboard makes it easy to interactively compare success rates and payload patterns across different launch sites without needing to re-run code for each view.

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
