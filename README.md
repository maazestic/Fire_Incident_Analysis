# 🔥 Fire Incident Analysis Project

## Overview
This project presents a comprehensive machine learning analysis of global fire incidents using NASA’s FIRMS (Fire Information for Resource Management System) satellite data. We apply data cleaning, exploratory data analysis (EDA), classification, regression, and anomaly detection to understand fire intensity, detection confidence, and global patterns of fire activity.

## Data Source
- **Dataset**: [NASA FIRMS Sample Data (July 12, 2023)](https://firms.modaps.eosdis.nasa.gov/content/notebooks/sample_viirs_snpp_071223.csv)
- **FIRMS Website**: [NASA Earthdata FIRMS Portal](https://www.earthdata.nasa.gov/data/tools/firms)
  
The dataset includes over 74,000 fire detection records captured by the VIIRS instrument on the Suomi NPP satellite. Features include:
- Brightness Temperatures (`bright_ti4`, `bright_ti5`)
- Fire Radiative Power (FRP)
- Scan and track values
- Confidence level
- Geographic coordinates
- Acquisition time

## Key Analyses
- **Data Cleaning**: Handling categorical encodings and engineering features.
- **EDA**: Visualizing FRP distributions, class imbalances, and spatial fire density.
- **Classification Models**: Logistic Regression and Random Forest to predict fire detection confidence levels.
- **Regression Model**: Gradient Boosting Regressor to estimate FRP.
- **Anomaly Detection**: Using Isolation Forest to flag unusual or extreme fire incidents.
- **Visualizations**: Correlation heatmaps, scatterplots, boxplots, and geospatial fire maps.

## Results
- Random Forest classification achieved an accuracy of **96%**, outperforming Logistic Regression.
- Gradient Boosting Regression achieved an RMSE of **16.23 MW** with an R² score of **0.50**.
- Brightness temperature (`bright_ti4`) was the strongest predictor of both confidence level and FRP.

## How to Run This Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Chetnas8/Fire_Incident_Analysis.git
   cd Fire_Incident_Analysis

