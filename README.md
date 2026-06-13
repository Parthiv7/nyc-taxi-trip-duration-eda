# NYC Taxi Trip Duration EDA

## Overview

This project performs Exploratory Data Analysis (EDA) on the NYC Taxi Trip Duration dataset to understand factors influencing taxi trip durations. The analysis focuses on trip patterns, passenger behavior, distance, speed, temporal trends, and vendor performance through statistical analysis and visualization.

---

## Problem Statement

The objective of this project is to explore and analyze NYC taxi trip data to identify key factors affecting trip duration and derive meaningful insights from the dataset through data cleaning, feature engineering, and visualization.

---

## Dataset Information

The dataset contains information about taxi trips in New York City, including:

- Vendor ID
- Pickup and Dropoff Coordinates
- Pickup Datetime
- Passenger Count
- Trip Duration

Dataset Size:
- 729,322 records

Target Variable:
- Trip Duration (in seconds)

---

## Project Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis
4. Feature Engineering
5. Correlation Analysis
6. Insight Generation

---

## Data Exploration

### Data Cleaning
- Missing Value Analysis
- Duplicate Record Checks
- Outlier Identification

### Data Preprocessing
- Datetime Conversion
- Feature Transformation
- Distance Calculation
- Speed Calculation

---

## Univariate Analysis

The following variables were analyzed individually:

- Vendor ID
- Passenger Count
- Trip Duration
- Distance
- Speed
- Total Trips per Hour
- Total Trips per Weekday
- Total Trips per Month

---

## Bivariate Analysis

Relationships between variables were analyzed using visualizations and statistical methods:

- Trip Duration vs Hour
- Trip Duration vs Weekday
- Trip Duration vs Month
- Trip Duration vs Vendor
- Distance vs Hour
- Distance vs Weekday
- Distance vs Month
- Distance vs Vendor
- Distance vs Trip Duration
- Average Speed vs Hour
- Average Speed vs Weekday
- Passenger Count vs Vendor
- Pickup vs Dropoff Locations

---

## Feature Engineering

Additional features were created to improve analysis:

- Pickup Hour
- Pickup Weekday
- Pickup Month
- Trip Distance
- Average Speed

### Correlation Analysis
- Correlation Matrix
- Heatmap Visualization

---

## Key Findings

- Most taxi trips are short-distance trips.
- Trip duration increases with trip distance.
- Peak traffic hours show increased trip durations and reduced average speeds.
- Taxi demand varies significantly across hours and weekdays.
- Vendor distribution is relatively balanced across trips.
- Pickup and dropoff locations exhibit distinct geographic patterns.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Geopy
- Jupyter Notebook

---

## Repository Structure

```
nyc-taxi-trip-duration-eda/
│
├── README.md
│
├── NYC_Taxi_EDA.ipynb
```

---

## Future Improvements

- Interactive dashboards using Plotly
- Geospatial visualizations using Folium
- Machine Learning models for trip duration prediction
- Advanced feature engineering

---

## Author

**Parthiv Das**

Electrical Engineering Undergraduate, DTU  
Data Engineer Associate at Fractal
