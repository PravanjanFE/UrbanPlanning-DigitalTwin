![Urban Traffic Simulation](./assets/cover-image.png)

# 🚦 Urban Traffic Simulation and Planning

Transforming urban traffic simulation and planning with a **real-time interactive platform** combining **ArcGIS, Unreal Engine, and TomTom traffic data**, the **CHS School – Urban Traffic Simulation & Planning Digital Twin** delivers **immersive geospatial accuracy** matched with **live traffic dynamics** for superior urban design insights.  

What if every city street's flow and congestion could be **seen and analyzed in a vivid 3D environment**, aligned perfectly to **real-world coordinates**?  
What if **real-time traffic data powered dynamic simulations** enabling planners and managers to make **smarter mobility decisions**?  

This project blends **live TomTom API data**, **custom 3D models**, and **verified GIS terrain** to realize that vision.  

---

## 📑 Contents
- [🌍 Overview](#-overview)  
- [🔄 Workflow Summary](#-workflow-summary)  
- [🎮 Interactive Features](#-interactive-features)  
- [📊 Monitoring Panels](#-monitoring-panels)  
- [🧪 Testing & Deployment](#-testing--deployment)  
- [🎯 Technology Stack](#-technology-stack)  
- [✅ Outcome](#-outcome)  

---

## 🌍 Overview
This platform visualizes **vehicle movements, congestion heatmaps, and urban layouts** precisely georeferenced to enable **real-time traffic management** and **urban planning analyses**.  

It integrates:  
- **Custom 3D school buildings**  
- **ArcGIS basemaps**  
- **Live traffic data**  

➡️ All displayed over a **geospatially accurate terrain** in **Unreal Engine**.  

---

## 🔄 Workflow Summary

1. **Data Acquisition** → Gathered **live TomTom traffic data** & **ArcGIS basemaps**; verified buildings via Google Street View & ground footage  
2. **3D Modeling** → Created **architecturally accurate school buildings**; imported surrounding city blocks from ArcGIS  
3. **ArcGIS Pro** → Exported **georeferenced basemap layers** (buildings, roads, environmental textures)  
4. **Unreal Engine Setup** →  
   - Initialized project from **Third Person template** with GIS plugins  
   - Created **roads with spline blueprints**  
   - Integrated **TomTom API** for live vehicle simulation  
   - Visualized congestion using **red-yellow-green spline gradients**  
5. **Interactive Features** → Enabled **traffic simulation toggles**, layered urban visualization, & dynamic planning workflows  
6. **UI & Development** → Built **interactive UI system** with user-friendly controls  
7. **Monitoring Panels** → Integrated live dashboards for **environment, energy, and asset capacity**  
8. **Testing & Deployment** → Debugged API integration, spline accuracy, terrain placement; packaged as interactive Unreal build  

---

## 🎮 Interactive Features
- **Location Bookmarks**:  
  - Placed at key areas  
  - Scale dynamically with distance  
  - Always face the camera  
  - Enable **smooth navigation** when selected  

---

## 📊 Monitoring Panels
- **Environment Panel** → Real-time display of temperature, humidity, airflow  
- **Power & Energy Panel** → Tracks electrical usage linked to racks & PDUs  
- **Asset & Capacity Panel** → Shows server utilization, rack space, and network traffic with **dynamic 3D highlights**  

---

## 🧪 Testing & Deployment
- **Testing** → Focused on API integration, spline accuracy, terrain placement, interactivity, and performance  
- **Deployment** → Packaged as **Windows executable**, with **VR support** for immersive exploration  

---

## 🎯 Technology Stack

### 🔹 Backend
1. Real-time traffic data via **TomTom APIs**  
2. Geospatial basemaps from **ArcGIS**  
3. Terrain capture & refinement: **RenderDoc, Blender**  

### 🔹 Frontend
1. **Unreal Engine** with GIS plugins (visualization & simulation engine)  
2. **Blender, ArcGIS exports** (content creation pipeline)  
3. **Unreal Blueprints** (UI & interactivity)  

---

## ✅ Outcome
The **Urban Traffic Simulation & Planning Digital Twin** combines:  
- **Real-time TomTom traffic data**  
- **Geospatial accuracy from ArcGIS**  
- **Immersive simulation via Unreal Engine**  

The **backend** powers data acquisition & processing (TomTom API, ArcGIS, RenderDoc, Blender), while the **frontend** delivers **interactive 3D simulation, visualization, and UI**.  
This system equips planners with **dynamic traffic insights**, enabling **better mobility decisions** and **smarter urban design workflows**.  

---
