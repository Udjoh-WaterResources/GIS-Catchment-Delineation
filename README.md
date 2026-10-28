# GIS Catchment Delineation & Hydrological Analysis

## Project Overview
This repository contains two hydrological terrain analysis projects completed in QGIS using GRASS GIS tools.

### 1. Foundational Exercise: Gothenburg & Stockholm
*   **Workflow:** SRTM 30m DEM processing, sink filling (`r.fill.dir`), flow accumulation (`r.watershed`), stream extraction, and vectorization.
*   **Output:** Delineated watersheds and vector stream networks overlaid on basemaps.

### 2. Advanced Capstone: Helge Å Basin (Kristianstad)
*   **Challenge:** The Helge Å basin features very flat topography, causing standard outlet tools to fail. 
*   **Solution:** Derived the stream network to locate the true outlet pixel. Extracted the full basin and calculated the catchment area using the Field Calculator (approx. 1,500 km²).
*   **Deliverable:** The final polygon was used as the spatial boundary for the System Dynamics water allocation model (see STELLA Repository).
