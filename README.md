![Urban Traffic Simulation](./assets/cover-image.png)

# 🚦 Urban Traffic Simulation and Planning

Transforming urban traffic simulation and planning with a **real-time interactive platform** combining **GIS, Unreal Engine, and TomTom traffic data**, the **Urban Traffic Simulation & Planning Digital Twin** delivers **immersive geospatial accuracy** matched with **live traffic dynamics** for superior urban design insights.  

What if every city street's flow and congestion could be **seen and analyzed in a vivid 3D environment**, aligned perfectly to **real-world coordinates**?  
What if **real-time traffic data powered dynamic simulations** enabling planners and managers to make **smarter mobility decisions**?  

This project blends **live TomTom API data**, **custom 3D models**, and **verified GIS terrain** to realize that vision.  

---

[▶ Watch Demo Video](https://drive.google.com/file/d/1W_4Q6nYBysNsCkzRRozM68-LyAOkkcdF/view?usp=drive_link)

---

## 📑 Contents
- [🌍 Overview](#-overview)  
- [🔄 Workflow Summary](#-workflow-summary)  
- [🎮 Interactive Features](#-interactive-features)
- [📊 Monitoring Panels](#-monitoring-panels)
- [🎯 Technology Stack](#-technology-stack)
- [✅ Outcome](#-outcome)  

---

## 🌍 Overview
This platform visualizes **vehicle movements, congestion heatmaps, and urban layouts** precisely georeferenced to enable **real-time traffic management** and **urban planning analyses**.  

It integrates:  
- **Custom 3D school buildings**  
- **GIS basemaps**  
- **Live traffic data**  

➡️ All displayed over a **geospatially accurate terrain** in **Unreal Engine**.  

---

## 🔄 Workflow Summary

1. **Data Acquisition** → Gathered **live TomTom traffic data** & **GIS basemaps**; verified buildings via Google Street View & ground footage  
2. **3D Modeling** → Created **architecturally accurate buildings**; imported surrounding city blocks from GIS data  
3. **GIS Pro** → Exported **georeferenced basemap layers** (buildings, roads, environmental textures)  
4. **Unreal Engine Setup** →  
   - Initialized project from **Blank template** with GIS plugins  
   - Created **roads with spline blueprints**  
   - Integrated **TomTom API** for live vehicle simulation  
   - Visualized congestion using **red-yellow-green spline gradients**  
5. **Interactive Features** → Enabled **traffic simulation toggles**, layered urban visualization, & dynamic planning workflows  
6. **UI & Development** → Built **interactive UI system** with user-friendly controls 
8. **Testing & Debugging** → Iterative testing to validate data accuracy and interaction fidelity (this is to be executed as per real time project deployment)
9. **Deployment** → Packaged as a Windows build/Pixel Streaming, optimized for performance 

---

## 🎮 Interactive Features
- **Location Bookmarks**:  
  - Placed at key areas  
  - Scale dynamically with distance  
  - Always face the camera  
  - Enable **smooth navigation** when selected  

---

## 📊 Monitoring Panels
- **Air Quality Index Panel** → Tracks universal & local air quality with **visual heatmaps**  
- **Pollen Index Panel** → Displays **live pollen levels** (tree, grass, weed) with severity indicators  
- **Flood Zone Panel** → Visualizes **real-time flood impact zones** for proactive safety  

---

## 🎯 Technology Stack

### 🔹 Backend
1. Real-time traffic data via **TomTom APIs**  
2. Geospatial basemaps from **GIS**  
3. Terrain capture & refinement: **RenderDoc, Blender**  

### 🔹 Frontend
1. **Unreal Engine** with GIS plugins (visualization & simulation engine)  
2. **Blender, GIS exports** (content creation pipeline)  
3. **Unreal Blueprints** (UI & interactivity)  

---

## ✅ Outcome
The **Urban Traffic Simulation & Planning Digital Twin** combines:  
- **Real-time TomTom traffic data**  
- **Geospatial accuracy from GIS**  
- **Immersive simulation via Unreal Engine**  

The **backend** powers data acquisition & processing (TomTom API, GIS, RenderDoc, Blender), while the **frontend** delivers **interactive 3D simulation, visualization, and UI**.  
This system equips planners with **dynamic traffic insights**, enabling **better mobility decisions** and **smarter urban design workflows**.  

---

## 🌐 Company Website
Visit us at [FourEdges.io](https://fouredges.io/)

---

## 🔐 Data Privacy & Security
Our **data handling approach** prioritizes **client data sovereignty** through:  
- **On-premises deployment**  
- **Comprehensive security controls**  
- **Transparent operational practices**  

All solutions operate **within client infrastructure**, ensuring:  
- Complete **data ownership and control**  
- Maintenance of **enterprise-grade security standards** throughout the **project lifecycle**

---
