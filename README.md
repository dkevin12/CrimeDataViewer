# GEOG 328 – Seattle Crime Data Explorer

> **Note:** This project is an extension of an original group project developed for GEOG 328.

### Original Project
- **Repository:** https://github.com/206ET/GEOG328_GroupAC2_CrimeData  
- **Live Website:** https://206et.github.io/GEOG328_GroupAC2_CrimeData/

---

## 📌 Project Description

The **Seattle Crime Explorer** is an interactive Web GIS application designed to visualize crime patterns across Seattle using real incident data from the Seattle Police Department (SPD). The application combines heatmaps, point-based visualization, and dynamic filtering to help users explore where crimes occur, which types are most common, and how crime patterns vary across neighborhoods and time periods.

The primary goal of this project is to make public safety data **accessible, intuitive, and meaningful** for residents, students, policymakers, and community organizations.

---

## 🎯 Project Goals

The Seattle Crime Explorer aims to deliver a **public-facing, interactive, and user-friendly Web GIS platform** with the following objectives:

### 1. Increase Data Accessibility
Public safety datasets are often difficult to interpret in raw table or spreadsheet form. This application transforms complex police data into a visual, map-based experience where spatial patterns are immediately visible.

### 2. Support Community Awareness
Users can identify crime hotspots, understand neighborhood-level trends, and explore how crime varies over time to make more informed safety decisions.

### 3. Support Policymaking and Urban Planning
By highlighting spatial and temporal crime patterns, the tool can assist organizations and government agencies in evaluating crime prevention strategies and resource allocation.

### 4. Promote Transparency
While police crime data is publicly available, it is rarely presented in an accessible or interactive format. This project emphasizes clear, responsible, and transparent data presentation.

Overall, the goal is to deliver a **high-quality**, **educational**, and **usable** Web GIS application that helps users better understand crime across Seattle.

---

## 🌐 Application URL

📍 **Live Website:**  
https://206et.github.io/GEOG328_GroupAC2_CrimeData/

---

## 🧭 Core Features & Functionality

### Zoom-Based Visualization
- Heatmap view when zoomed out  
- Point-based markers when zoomed in  
- Smooth Mapbox-powered transitions  

### Crime Type Filtering
- Violent Crime  
- Property Crime  
- Other Crime  
- All Crime Types  

### Neighborhood Filtering
- Auto-populated dropdown  
- Based on official Seattle neighborhood boundaries  

### Date Range Filtering
- Converts inconsistent SPD date formats into unified timestamps  
- Supports seasonal, monthly, and multi-year analysis  

### Interactive Popups
Each incident popup displays:
- Crime category & subcategory  
- Report number  
- Neighborhood  
- Precinct and beat  
- Offense date  

### Real-Time Statistics Panel
- Total incidents based on current filters  
- Percentage breakdowns by crime type  
- Category-level counts  
- Top neighborhoods  
- Temporal coverage summaries  

### Fully Responsive Design
- Optimized for desktop, tablet, and mobile  
- Collapsible sidebar  
- Dynamic map resizing using `map.resize()`  

---

## 📊 Data Sources

### Seattle Police Department Crime Data (2008–Present)
https://data.seattle.gov/Public-Safety/SPD-Crime-Data-2008-Present/tazs-3rd5

### Seattle Neighborhood Boundaries
https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::neighborhood-map-atlas-neighborhoods

### Kaggle Crime Dataset (Supplementary)
https://www.kaggle.com/datasets/adoumtaiga/crime-data-set

---

## 🧰 Technologies & Web Services

### Libraries
- **Mapbox GL JS (v3.2.0)**

### Web Services & Formats
- GitHub Pages  
- Mapbox Basemap Tiles  
- GeoJSON  

---

## 🤖 AI Use Disclosure

ChatGPT was used to assist with:
- Debugging JavaScript code  
- Improving responsive CSS layouts  
  

All application logic, data processing decisions, and testing were completed by **Group AC2**.

---

## 👥 Team Members

- **Yeabkal S**  
- **Emmanuel T**  
- **Kevin D**  
- **Amartya C**  
- **Girum W**
