# NDVI Analysis Project
## Project Overview

This project involves analyzing the Normalized Difference Vegetation Index (NDVI) using Sentinel-2 satellite imagery.  
The focus is on calculating NDVI for a specific area of interest (AOI) in Maine, clipping the NDVI to this sub-AOI, and visualizing the changes over time through static maps and dynamic animations.

## Data Description

The data used in this project includes:
- Sentinel-2 satellite images: These images provide multi-spectral data which is essential for calculating NDVI. The data is stored in a NetCDF file (```geospatial_test_datacube.nc```).
- GeoJSON file: This file (```geospatial_sub_aoi.geojson```) defines the sub-Area of Interest (sub-AOI) for which the NDVI is specifically analyzed and visualized.

## Setup and Running

1. Clone the repository
```commandline
git clone https://github.com/albertolanzini/maine-remote-sensing-data.git
cd maine-remote-sensing-data
```
2. Run Jupyter Notebook (you can install it following the instructions in https://jupyter.org/install)
```commandline
jupyter notebook
```
3. Run the cells and enjoy!

**Note** the animations and interactive maps cannot be seen through GitHub, so for the _full_ experience clone the repo!
