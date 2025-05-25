# 🌍 Maximum Elevation Finder - Mt. Everest Region

This project demonstrates how to use elevation data (SRTM) and Python tools to analyze the terrain around Mt. Everest and find the highest point—Mt. Everest itself.

## 📌 Objectives

- Merge and reproject multiple SRTM tiles using Rasterio
- Analyze elevation values and find the maximum height
- Understand the CRS and unit handling in elevation rasters

## 🧠 What I Learned

I initially assumed I needed to convert the CRS to get correct elevation, but later understood that the **vertical units were already in meters**. Through this mistake, I learned how to reproject raster data using Rasterio and gained hands-on experience with geospatial raster processing.

## 🛠️ Tools Used

- Python 🐍
- Rasterio
- NumPy
- Jupyter Notebook

## 📂 Folder Structure

notebook/ → Contains analysis notebook
data/ → Placeholder for input SRTM tiles (not uploaded due to size)
images/ → Output plot images

## 🔒 Note

The SRTM raster files are not included in the repository because they exceed GitHub's file size limits. You can download the data from [USGS EarthExplorer](https://earthexplorer.usgs.gov/).

---

🎓 **Author**: Dheepika  
📅 **Date**: May 2025  
📁 **Project Type**: Beginner GeoRaster Analysis  