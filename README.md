# 🌍 Paris Urban Heat & Green Space Inequality

A data-driven exploration of how green space distribution and income disparities influence exposure to urban heat in Paris.

This project combines open geospatial data, socioeconomic indicators, and climate-relevant metrics to map and measure environmental inequality across the city's 20 arrondissements. The goal is to identify vulnerable communities and support more equitable urban planning.

---

## 📌 Project Objectives

- Quantify green space per arrondissement
- Compare green coverage to median disposable income and poverty rate
- Map urban cooling zones ("îlots de fraîcheur") across Paris
- Visualize and interpret spatial inequality in access to green infrastructure

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

- Python: Pandas, GeoPandas
- Visualization: Matplotlib, Seaborn, Folium
- Mapping: QGIS (optional), Google Colab or Jupyter
- Dashboard: Streamlit (optional)

---

## 🙋 About the Author

**Laura Monteiro**  
Brazilian financial analyst transitioning into data science and climate impact research.  
Passionate about sustainability, inequality, and AI for public good.

- 📍 Based in Paris (for this project)
- 🌱 Focused on urban climate solutions
- 🌎 LinkedIn: [linkedin.com/in/laurammonteiro](https://linkedin.com/in/laurammonteiro)

