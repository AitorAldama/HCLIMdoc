---
layout: default
title: General Description
---

![HCLIM logo](logos/DMI_HCLIMlogo_Colours.png)
<p align="center">
 <img src="logos/HCLIM_ProjectImage_Colours_1500px.png" alt="HCLIM Logo" width="750">
</p>

The **HARMONIE-Climate (HCLIM)** is a regional climate model framework developed jointly by several European national meteorological services. It is the *climate* version of the HIRLAM–ALADIN Research on Mesoscale Operational numerical weather prediction (NWP) in Euromed (HARMONIE) system, with HCLIM development closely linked to HARMONIE advancements.  

HCLIM includes three different atmospheric physics packages—**AROME, ALARO,** and **ALADIN**—each designed for specific horizontal resolutions and both hydrostatic and non-hydrostatic dynamics. 

## Key Features:
- **Supports multiple physics configurations:**  
  - **HCLIM-ALADIN** operates as a hydrostatic model for simulations with grid spacing close to or larger than 10 km.  
  - **HCLIM-ALARO** is typically used for grid sizes of 4 km and larger, employing the hydrostatic version.  
  - **HCLIM-AROME** is designed for convection-permitting resolutions, explicitly resolving deep convection and generally applied at horizontal resolutions finer than 4 km.  

- **Advanced surface parameterization:**  
  The surface scheme in HCLIM is **SURFEX** (Surface Externalisée; [Masson et al., 2013](https://gmd.copernicus.org/articles/6/929/2013/)), which represents subgrid surface heterogeneity using four tiles: continental natural surfaces, sea, inland water, and urban areas.  

- **Versatile regional climate applications:**  
  HCLIM is used for regional climate projections across various domains, including Europe, the Arctic, and Antarctica.  

- **Designed for climate scenario development and extreme weather studies:**  
  The model helps create regional climate scenarios, evaluate extreme weather in a warming climate, and study physical and chemical processes within the Earth system.  

- **Ongoing development by European meteorological institutes:**  
  HCLIM is developed by a consortium of [European national meteorological institutes](members.md).  

- **References:**  
  [List of publications](references.md) in which HCLIM has been used.  

The latest version, **HCLIM46**, succeeds earlier versions **HCLIM43**, **HCLIM38** ([Belušić et al., 2020](https://gmd.copernicus.org/articles/13/1311/2020/)) and **HCLIM36** ([Lindstedt et al., 2015](https://a.tellusjournals.se/articles/10.3402/tellusa.v67.24138); [Lind et al., 2016](https://journals.ametsoc.org/view/journals/clim/29/10/jcli-d-15-0463.1.xml)).  
