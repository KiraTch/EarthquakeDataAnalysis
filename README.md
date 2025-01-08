# Earthquake Data Analysis Project

## Overview
This repository contains a dataset and analysis tools for studying earthquake events. The dataset includes information about earthquake locations (latitude and longitude), focal depths, and magnitudes on the Richter scale.

## Dataset Description
The dataset (`quake.csv`) contains detailed information about 2,178 earthquake events with the following attributes:

- **Focal Depth**: The depth of the earthquake's focus below the Earth's surface (measured in kilometers)
- **Latitude**: Geographic latitude of the earthquake epicenter (in decimal degrees)
- **Longitude**: Geographic longitude of the earthquake epicenter (in decimal degrees)
- **Richter**: Magnitude of the earthquake on the Richter scale

## Data Format
The data is stored in CSV (Comma-Separated Values) format with the following columns:
```
Focal depth,Latitude,Longitude,Richter
```

### Prerequisites
- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn (for visualization)

## Analysis Features
- Geographic distribution of earthquakes
- Depth analysis
- Magnitude distribution
- Correlation studies between depth and magnitude
- Temporal patterns (if timestamp data is added)

## Visualization Examples
The repository includes scripts for creating various visualizations:
- Earthquake location maps
- Magnitude distribution histograms
- Depth vs. magnitude scatter plots
- Geographic heat maps
