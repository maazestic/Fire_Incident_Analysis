# Fire Incident Analysis 🔥

![Fire Incident Analysis](https://img.shields.io/badge/Release-v1.0.0-brightgreen)  
[Download the latest release](https://github.com/maazestic/Fire_Incident_Analysis/releases)

---

## Overview

Welcome to the **Fire Incident Analysis** repository! This project provides a comprehensive machine learning analysis of global fire incidents using NASA FIRMS satellite data. Our goal is to uncover insights into fire confidence and intensity across various regions. The analysis includes essential steps such as data cleaning, exploratory data analysis (EDA), classification, regression, anomaly detection, and effective visualizations.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Data Sources](#data-sources)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Analysis](#analysis)
   - [Data Cleaning](#data-cleaning)
   - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
   - [Modeling](#modeling)
     - [Classification](#classification)
     - [Regression](#regression)
     - [Anomaly Detection](#anomaly-detection)
7. [Visualizations](#visualizations)
8. [Insights](#insights)
9. [Contributing](#contributing)
10. [License](#license)
11. [Contact](#contact)

---

## Introduction

Fire incidents pose significant risks to both natural ecosystems and human life. Understanding these incidents can help in better preparedness and response strategies. This repository aims to analyze fire data collected from NASA's FIRMS satellite. We employ various machine learning techniques to identify patterns and predict fire incidents.

---

## Features

- Comprehensive analysis of global fire incidents
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA) to uncover trends
- Machine learning models for classification and regression
- Anomaly detection to identify unusual fire patterns
- Visualizations to present key insights
- Highlighting feature importance in predictions

---

## Data Sources

The primary data source for this analysis is NASA's FIRMS satellite data. This data provides real-time information about fire incidents globally. The dataset includes various features such as fire location, confidence level, and intensity.

---

## Installation

To get started with this project, you need to have Python installed on your machine. You can follow these steps to set up the environment:

1. Clone the repository:
   ```bash
   git clone https://github.com/maazestic/Fire_Incident_Analysis.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Fire_Incident_Analysis
   ```

3. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

5. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

Once you have set up the environment, you can start the analysis. Open the Jupyter Notebook provided in the repository to follow along with the analysis steps.

To launch Jupyter Notebook, run:
```bash
jupyter notebook
```

You can also execute the scripts directly if you prefer.

---

## Analysis

### Data Cleaning

Data cleaning is crucial for any analysis. In this project, we handle missing values, remove duplicates, and convert data types as needed. This step ensures that our models work with high-quality data.

### Exploratory Data Analysis (EDA)

EDA helps us understand the dataset better. We visualize distributions, correlations, and trends in the data. Key visualizations include:

- Histograms for feature distributions
- Heatmaps for correlation analysis
- Time series plots for fire incidents over time

### Modeling

We employ various machine learning models to analyze the data.

#### Classification

For classification tasks, we use algorithms like Logistic Regression and Random Forest. These models help us predict whether a fire incident will occur based on historical data.

#### Regression

Regression models, including Gradient Boosting, allow us to predict the intensity of fire incidents. We evaluate model performance using metrics like Mean Absolute Error (MAE) and R-squared.

#### Anomaly Detection

Anomaly detection techniques identify unusual fire incidents. This step is crucial for early warning systems.

---

## Visualizations

Visualizations play a key role in understanding the data. We create various plots to represent our findings:

- **Fire Incident Heatmap**: Shows the density of fire incidents across regions.
- **Time Series Analysis**: Displays trends over time.
- **Feature Importance Plot**: Highlights which features contribute most to our predictions.

---

## Insights

Our analysis reveals several key insights:

- Certain regions experience more fire incidents than others.
- Specific features, such as temperature and humidity, significantly impact fire intensity.
- Anomalies in fire incidents can indicate underlying issues that require further investigation.

---

## Contributing

We welcome contributions to improve this project. If you have suggestions or find issues, please open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For any questions or feedback, feel free to reach out:

- **Author**: Your Name
- **Email**: your.email@example.com

---

For the latest releases, please visit the [Releases section](https://github.com/maazestic/Fire_Incident_Analysis/releases).