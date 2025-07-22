# 🌍 Paris Urban Heat & Green Space Inequality

A data-driven exploration of how green space distribution and income disparities influence exposure to urban heat in Paris.

This project combines open geospatial data, socioeconomic indicators, and climate-relevant metrics to map and measure environmental inequality across the city's 20 arrondissements. The goal is to identify vulnerable communities and support more equitable urban planning.

---

## 📌 Project Objectives

- Quantify green space per arrondissement
- Compare green coverage to median disposable income and poverty rate
- Map urban cooling zones ("îlots de fraîcheur") across Paris
- Explore lived experience through field visits to selected neighborhoods
- Support public awareness of climate inequality in urban environments

---

## 🗺️ Why This Matters

Urban heat disproportionately affects low-income communities with limited access to green or shaded areas. Paris, like many cities, is experiencing more frequent heatwaves, making it essential to identify areas at risk and improve urban resilience strategies.

---

## 📂 Folder Structure

/data → Cleaned and raw CSV/GeoJSON files
/notebooks → Jupyter/Colab notebooks (EDA, cleaning, modeling)
/scripts → Modular Python scripts (e.g., merge, metrics)
/figures → Maps, charts, and visual assets

---

## 🗃️ Datasets Used

| Dataset                        | Source & Description                                   |
|-------------------------------|--------------------------------------------------------|
| `espaces_verts.geojson`       | [opendata.paris.fr](https://opendata.paris.fr/explore/dataset/espaces_verts/export/) – Green space polygons in Paris |
| `ilots_de_fraicheur.geojson`  | [opendata.paris.fr](https://opendata.paris.fr/explore/dataset/ilots-de-fraicheur-espaces-verts-frais/) – Urban cooling zones |
| `arrondissements.geojson`     | [opendata.paris.fr](https://opendata.paris.fr/explore/dataset/arrondissements/export/) – Official admin boundaries |
| `income_paris_2018.csv`       | [INSEE – FiLoSoFi dataset](https://www.insee.fr/en/statistiques/6443358) – Median disposable income & poverty in 2018 |

---

## 🧰 Tools & Technologies

- **Python**: Pandas, GeoPandas, Matplotlib, Seaborn
- **Mapping**: Folium, QGIS (optional)
- **Environment**: Google Colab, GitHub

---

## 🙋 About the Author

**Laura Monteiro**  
Brazilian financial analyst transitioning into data science and climate impact research.  
Passionate about sustainability, inequality, and AI for public good.

- 📍 Based in Paris (for this project)
- 🌱 Focused on urban climate resilience
- 🌎 LinkedIn: [linkedin.com/in/laurammonteiro](https://linkedin.com/in/laurammonteiro)

