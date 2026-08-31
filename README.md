# 🚨 RES-Q: Smart Landslide Early Warning & Rescue Management System

**RES-Q** is a comprehensive Mobile UI/UX design solution engineered to predict, monitor, and manage landslide disasters in real-time. By connecting continuous geological sensor/LiDAR data with instant emergency alert systems and response team logistics, RES-Q aims to mitigate loss of life and accelerate disaster response operations in high-risk terrain.

---

## 📌 Project Overview

Landslides are rapid, highly destructive disasters that often leave minimal response time. **RES-Q** addresses this critical challenge through a two-fold approach:
1. **Pre-Disaster Monitoring & Early Warning:** Continuously analyzing slope stability, moisture levels, and geological strain via live spatial data and automated SMS dispatch.
2. **Post-Disaster Rescue Coordination:** Providing emergency responders with real-time incident routing, casualty tracking, team location mapping, and backup dispatch management.

---

## ✨ Key Features & Screen Overview

### 1. 🏠 Main Operational Dashboard (`Home Screen`)
* **Live Situation Map:** Topographical LiDAR map overlay illustrating landslide risk zones, active rescue team positions, and trapped user mobile signals.
* **Automated Emergency Dispatch:** One-tap action button to trigger widespread automated SMS alerts to residents in high-risk zones.
* **Operational Insights:** Direct access to **Continuous Analysis**, **Live Updates**, and **Resource Management**.
* **Quick Action Feeds:** Direct access to Emergency Reports, Red Alert Notifications, and Active Incident Cards.

---

### 2. 📊 Continuous Analysis & Risk Modeling (`Analysis Screen`)
* **3D Slope Stability Heatmaps:** Visualizes real-time geological risk levels (Red = Critical, Orange/Yellow = Moderate, Blue/Green = Stable).
* **Sensor Integration:** Real-time data streams tracking:
  * **Moisture & Fluid Content**
  * **Inclinometer & Slope Instability metrics**
  * **Seismic / Geotechnical strain indicators**
* **Geological Section Breakdown:** Multi-angle monitoring of slope deformation and fault line behavior.

---

### 3. 🚑 Incident Location & Response Tracking (`Location Screen`)
* **Casualty Estimation:** Live estimate of affected individuals (~5 reported) to help rescuers allocate resources effectively.
* **Active Response Teams Tracking:** Real-time GPS tracking for active units (e.g., Firefighters, Ambulances).
* **Backup Unit Management:** Displays nearby available backup support (e.g., 2 teams nearby) with one-tap contact capabilities.
* **Incident Event Timeline:** Granular logging of incident milestones:
  * `09:55` — Incident Reported
  * `09:57` — Mass SMS Alert Sent
  * `10:00` — Rescue Teams Dispatched
  * `10:25` — On-Site Arrival Confirmed

---

### 4. 🗺️ Safe Evacuation Route Navigation (`Evacuation Screen`)
* **Dynamic Route Calculation:** Real-time GPS routing avoiding active hazard zones, blocked paths, and debris fields (e.g., route guidance near vulnerable hill stretches).
* **Safe Zone Metrics:** Direct display of distance and estimated travel time to the nearest designated safe shelter / emergency drop point.

---

## 📱 Navigation Structure

The app utilizes a standard 4-tab bottom navigation bar for seamless access during high-stress operations:
1. 📍 **Map:** Live spatial map displaying hazard alerts, victim telemetry, and navigation.
2. 🔴 **Live Operation:** Active command screen for ongoing rescue operations and team management.
3. ⚠️ **New Incident:** Rapid reporting panel for new landslide occurrences or emergency calls.
4. ⚙️ **Settings:** System preferences, sensor connectivity, and user profile management.

---

## 🎨 Design System & Palette

The UI design uses high-contrast, functionally color-coded elements designed for clear visibility under high-stress field conditions:

| Element | Color Hex | Visual Purpose |
| :--- | :--- | :--- |
| **Critical Red Alert** | `#D32F2F` / `#E53935` | Emergency banners, high-risk heatmaps, priority incident cards |
| **Warning Orange** | `#D86337` | Secondary actions, Continuous Analysis headers, Evacuation indicators |
| **Active Neutral / Grey** | `#A0A0A0` / Light Grey | Information containers, timeline logs, secondary metrics |
| **Safe / Success Green**| `#4CAF50` | Verified status, safe route paths, active backup indicators |

---
**Team Member & Collaborator: Anushka Singh 
Co-designed the RES-Q UI/UX workflow and system architecture.

## 📁 Repository Structure

```micro
RES-Q-Figma-UI/
├── assets/
│   ├── ResQ home page.png
│   ├── Landslide analysis.png
│   ├── ResQ Safe Evacuation route.png
│   └── ResQ location.png
├── Figma/
│   └── RES_Q_Landslide_System.fig
└── README.md
