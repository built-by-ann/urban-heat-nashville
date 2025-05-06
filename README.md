# 🌇 Urban Heat in Nashville: The Impact of Impervious Surfaces on Surface Temperatures

**Author**: Ann Mathew  
**Tool used**: QGIS  
**Course**: ANTH 3621
**Fall 2024

## 📌 Introduction

Urbanization can have a major impact on local climates through the development of impervious surfaces such as roads and buildings, which absorb and retain heat. This project examines the relationship between impervious surface coverage and land surface temperatures (LST) in Nashville using GIS.

By focusing on the Urban Heat Island (UHI) effect, I aim to address three research questions:
1. How are impervious surfaces distributed across Nashville?
2. How does LST vary in areas with different levels of impervious surface coverage?
3. What spatial patterns can we observe when comparing LST and impervious surface data?

---

## 🛰️ Methods

I used:
- **MODIS LST (MOD11A2)** for surface temperature data
- **NLCD 2019** for impervious surface coverage
- **Community Planning Area boundaries** from Nashville GIS to define the study area

Steps:
- Reprojected all layers to EPSG:4326
- Clipped raster layers to the Nashville planning area boundary
- Created categorized intervals for impervious surfaces
- Generated heatmaps and overlay maps in QGIS
- Added color-coded legends for clarity

All processing and analysis were done in QGIS.

---

## 📊 Results

- **LST Map (Figure 1)**: Higher temperatures (27–30°C) appear in downtown/urban zones; cooler zones (20–23°C) are found in green and rural areas.
- **Impervious Surface Map (Figure 2)**: Dense development (>90%) corresponds with high impervious surface percentages in central Nashville.
- **Overlay Map (Figure 3)**: Hot zones align with impervious surfaces >70%, showing a clear UHI pattern.

---

## 💬 Discussion

The analysis supports the existence of a **strong positive correlation** between impervious surface coverage and elevated LST. Urbanized areas with dense, impermeable infrastructure show more heat buildup than vegetated or rural areas. This reinforces the Urban Heat Island concept as a relevant local concern for Nashville.

---

## 🌱 Future Work

- Explore **seasonal patterns** in temperature using multiple time points
- Analyze **effectiveness of green infrastructure** (e.g., parks, green roofs) for urban cooling
- Support urban planners with GIS insights to mitigate heat stress

---

## 📂 Files in this Repo

- [`poster/urban-heat-nashville-poster.pdf`](poster/urban-heat-nashville-poster.pdf) – final project poster
- [`data/data_sources.md`](data/data_sources.md) – all data used and where to get it
- [`figures`](figures) – maps of figures 1, 2, and 3
