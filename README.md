# 🗺️ GeoPandas Beginner Tutorial: Mapping Cardiovascular Mortality in Miami

This project is a beginner-friendly tutorial on using **GeoPandas** to explore and visualize real-world geospatial data. We use a public dataset on **cardiovascular disease mortality by ZIP code** in **Miami-Dade County (2010)** to walk through spatial analysis and interactive map creation.

## 📌 Project Goals

- Learn how to read and work with GeoJSON and shapefiles using GeoPandas
- Create static and interactive choropleth maps
- Perform simple spatial analysis like calculating area
- Visualize public health data to identify patterns geographically

## 📁 Dataset Used

**Dataset Name**: Cardiovascular Mortality by ZIP Code (2010)  
**Source**: [Miami-Dade County Open Data Hub](https://gis-mdc.opendata.arcgis.com/)  
**Fields**:
- `ZIPCODE`: 5-digit ZIP code
- `DEATHCOUNT`: Number of cardiovascular deaths
- `RATE`: Deaths per 1,000 population
- `geometry`: ZIP code boundary polygons

## 🔧 Technologies Used

- Python 3.x
- GeoPandas
- Folium
- Matplotlib
- Google Colab (optional)

## 🧪 Setup Instructions

1. Clone this repo or upload the notebook to Google Colab
2. Install dependencies:
   ```bash
   pip install geopandas folium matplotlib
