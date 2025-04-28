# 🌍 Pollution Hotspot Detection and Visualization

## Overview
This project analyzes pollution data to identify the **most polluted cities** and visualize them accurately on an **interactive Mapbox scatter plot**.  
The goal is to provide clear insights into geographical areas with high pollution concentration.

---

## Features
- **Data Cleaning**:  
  Handles missing (`NaN`) values to ensure stable and error-free plotting.

- **Hotspot Identification**:  
  Selects the most polluted cities based on pollution averages.

- **Interactive Mapping**:  
  Uses Plotly's `scatter_mapbox` to plot pollution hotspots with dynamic zoom, hover info, and color gradients based on pollution intensity.

- **Error Handling**:  
  Prevents crashes by pre-validating input data for plotting.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd air-quality-analysis-and-pollution-hotspot-detection
   Usage
##Prepare your pollution data:

#Ensure your dataset contains at least the following columns:

city

latitude

longitude

station

pollutant_avg

#Run the notebook: Open and execute the DSPROJECT (2).ipynb notebook to process the data and generate the pollution hotspot map.

##View the Results:

The map will display with:

Marker color and size based on pollution average.

Station names on hover.

Focus zoom on major polluted areas.

##Project Structure

Edit
├── DSPROJECT (2).ipynb     # Main Jupyter Notebook
├── README.md               # Project description file
└── data/                   # (Optional) Folder to keep CSV or input files
Example Output
Interactive Map showing:

Large markers for highly polluted areas.

Small markers for relatively less polluted hotspots.

Hover labels showing the station name.



##Known Issues
#NaN Handling:
The project currently drops rows with missing pollutant_avg values.
In future updates, imputation techniques could be explored instead of dropping data.

##Future Improvements
Add city-level aggregation to highlight average pollution per city instead of individual stations.

Allow dynamic selection of pollutant types (e.g., PM2.5, NO2, SO2).

Enable date filtering for time-series pollution trends.

##Contributors
[sabeena] – Initial work and maintenance


