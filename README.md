# Global Burden & Spatial Visualization of Dengue Fever

An R geospatial analysis tracking global dengue fever occurrence and annual percentage changes over time.

![R](https://img.shields.io/badge/Made%20with-R-276DC3?style=flat&logo=r&logoColor=white)
![ggplot2](https://img.shields.io/badge/Visualization-ggplot2%20%7C%20gganimate-blue?style=flat)

---

## Annual Change in Dengue Cases (2022–2025)
<p align="center">
  <img src="file2ccc57524d92.gif" alt="Annual Change in Dengue Cases Worldwide" width="850"/>
</p>

## Spatial Distribution Overview
<p align="center">
  <img src="dengue_spatial.PNG" alt="Global Dengue Spatial Map" width="850"/>
</p>

---

## Repository Structure
* `dengue_global_burden.Rmd` — R Markdown source code for data processing, spatial mapping, and animation.
* `dengue_global_burden.nb.html` — Rendered R Notebook output.
* `dengue_spatial.PNG` — Static global distribution map.
* `file2ccc57524d92.gif` — Animated map showing year-over-year percentage changes.

## Key Methods & Packages
* **Spatial Handling:** `sf`
* **Data Wrangling:** `dplyr`
* **Visualization & Animation:** `ggplot2`, `gganimate`, `ggrepel`, `gifski`
*
