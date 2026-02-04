# England’s Edge: Mapping Coastal Erosion with Geo AI (2000–2025)

**Author:** Elizabeth Gronski
**Course:** DSA 8530 – Geo AI & Satellite Image Analysis
**Institution:** University of Missouri, Institute of Data Science and Informatics

---

## Project Overview

This project explores **coastal erosion and land cover change along England’s coastline**, with a focused case study on **Yorkshire**, using satellite imagery and geospatial AI techniques spanning **2000–2025**.

By blending **Landsat**, **Sentinel-2**, and **digital elevation models**, this project asks:

> *Where is the coast moving, how fast, and what’s changing alongside it?*

The results are displayed in maps and metrics that track shoreline migration, vegetation change, built-up expansion, and coastal vulnerability.

---

## Key Questions

* How has Yorkshire’s coastline shifted over the past 25 years?
* Where are erosion and accretion hotspots most pronounced?
* How do land cover changes (vegetation vs. built-up areas) relate to shoreline movement?
* Which low-lying areas may be most vulnerable based on elevation and terrain?

---

## Data & Tools

### Satellite Data

* **Landsat (2000–2025):** Long-term shoreline detection and change analysis
* **Sentinel-2:** High-resolution land cover indices (NDVI, NDBI)

### Elevation Data

* **DEM / SRTM:** Coastal elevation and vulnerability context

### Platforms & Libraries

* **Google Earth Engine (GEE):** Core analysis environment
* **JavaScript (GEE API):** Shoreline extraction, masking, vectorization
* **GIS Visualization:** Change maps, hotspot identification, and animations

---

## Methods

1. **Water Detection:** Separate land from sea using spectral indices and cloud masking.
2. **Shoreline Extraction:** Convert water boundaries into vector shorelines for multiple years.
3. **Change Analysis:** Measure shoreline movement and calculate erosion/accretion trends.
4. **Land Cover Indices:** Use NDVI and NDBI to track vegetation and urban change near the coast.
5. **Elevation Context:** Overlay shoreline change with DEM data to highlight vulnerable zones.

---

## Outputs

* **Shoreline change maps** (2000–2025)
* **Erosion and accretion hotspots**
* **NDVI & NDBI land cover change maps**
* **Coastal vulnerability insights** using elevation data

---

## Key Takeaways

* Yorkshire’s coastline shows **non-uniform change**, with clear erosion hotspots.
* Land cover dynamics near the coast often mirror shoreline behavior.
* Elevation adds critical context, highlighting areas where small shoreline shifts may have large impacts.

---

## Limitations

* Shoreline position is sensitive to tides, seasonal variability, and image resolution.
* DEM-based vulnerability provides context, not predictions.
* Results emphasize **patterns and trends**, not parcel-level precision.

---

## Why This Matters

Coastal erosion affects infrastructure, ecosystems, and communities. By combining **remote sensing, geospatial AI, and long-term satellite records**, this project demonstrates how data-driven tools can support coastal monitoring and informed decision-making.

---

## AI Usage Note

AI tools were used for **methodological guidance, debugging, and writing clarity**. All analysis design, interpretation, and final conclusions are the author’s own.
