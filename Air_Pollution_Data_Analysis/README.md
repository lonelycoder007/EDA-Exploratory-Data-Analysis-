# Air Data Analysis

This repository contains Python code for conducting exploratory data analysis (EDA) on air quality data. The analysis involves cleaning, preprocessing, and visualizing air quality metrics across different locations and states.

## Requirements

- Python 3.x
- Libraries: NumPy, Pandas, Matplotlib, Seaborn

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/air-data-analysis



# Project Overview

## Data Cleaning

- The dataset (`dataset.csv`) is loaded using Pandas, and basic information is displayed using `df.head()` and `df.info()`.

- Missing values are handled, and the percentage of missing values for each column is calculated.

- Irrelevant columns (`agency`, `location_monitoring_station`, etc.) are dropped.

## Data Transformation

- The `type` column is refined into three categories: 'Residential,' 'Industrial,' and 'Other'.

- Visualizations are created to show pollution levels across different areas, states, and types.

## Exploratory Data Analysis (EDA)

- Bar plots and heatmaps visualize the median values of pollutants like SO2, NO2, RSPM, SPM, and PM2.5 across states and years.

- Scatter plots and a correlation matrix explore relationships between different pollutants.

## Time Analysis

- A new 'year' column is created from the 'date' column.

- Heatmaps depict the average pollutant levels by state and year.

## Location Analysis

- Bar plots showcase pollutant levels (NO2, SO2, PM10, SPM) for the first and last 50 locations.

- Heatmap visualizations provide a detailed overview of pollution levels for specific pollutants.

# Conclusion

This project offers a comprehensive analysis of air quality data, providing insights into pollutant levels across locations and years. Feel free to customize and extend the analysis based on your specific requirements.
