# 🌊 2D Flood Modeling of the Tawa Basin, India using HEC-RAS

Welcome to my hydrodynamic modeling project of the **Tawa River Basin**, Madhya Pradesh, India! This project leverages the **2D HEC-RAS** modeling framework to simulate flood depth and velocity distribution, aiding in flood risk assessment and disaster preparedness.

![Tawa Basin Flood Depth](Images/depth_map.png)

---

## 📌 Project Objective

> To simulate flood inundation across the Tawa Basin using 2D HEC-RAS, and visualize key flood parameters such as **depth** and **velocity** under specific hydrological conditions.

---

## 🗺️ Study Area

The **Tawa Basin** is a key sub-watershed of the Narmada River Basin in Central India. This area is prone to seasonal flooding, which affects nearby towns and agricultural zones.

📍 Location: Madhya Pradesh, India  
🛰️ Terrain Source: SRTM/Copernicus DEM  
🌧️ Simulation Date: 14 May 2010 *(for scenario testing)*

---

## 🔧 Tools & Technologies Used

| Tool        | Purpose                          |
|-------------|----------------------------------|
| **HEC-RAS 6.0+** | 2D hydraulic modeling         |
| **RAS Mapper**   | Visualization of flood results |
| **QGIS**         | Terrain and vector data prep |
| **Remote Sensing** | DEM & LULC acquisition    |

---

## 📂 Folder Structure

```bash
TawaBasin_HECRAS_2D_Model/
│
├── Images/               # Result maps (depth, velocity, flood extent)
├── RAS_Files/            # HEC-RAS geometry & plan files
├── GIS_Data/             # DEM, shapefiles, basin boundaries
├── Docs/                 # Summary report or poster
├── Methodology/          # Flowchart and data pipeline
└── README.md             # This file
