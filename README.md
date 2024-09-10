# Car Fuel and Emissions Analysis

This repository contains a machine learning and data visualization project focused on analyzing car fuel consumption and emissions data from 2000 to 2013. The project involves predicting CO2 emissions, clustering vehicles based on emissions and fuel efficiency, and predicting fuel efficiency based on vehicle characteristics.

## Project Overview

The goal of this project is to explore the relationships between vehicle attributes and their impact on fuel efficiency and emissions. By using various machine learning techniques, the project provides insights into:

1. CO2 Emissions Prediction:
   - Model Used: Linear Regression
   - Objective: Predict CO2 emissions based on vehicle characteristics such as engine capacity, fuel type, and fuel efficiency metrics.

2. Clustering Vehicles:
   - Model Used: KMeans Clustering
   - Objective: Identify natural clusters of vehicles based on their emissions and fuel efficiency metrics, providing insights into similarities between vehicle groups.

3. Fuel Efficiency Prediction:
   - Model Used: Random Forest Regression
   - Objective: Predict vehicle fuel efficiency (combined metric) based on attributes like engine capacity, fuel type, and urban/extra urban fuel consumption.

## Dataset

The dataset used in this project is from 2000 to 2013 and includes various attributes related to vehicles, such as:

- Engine capacity
- CO2 emissions
- Fuel efficiency metrics (urban, extra-urban, and combined)
- Transmission type
- Fuel type
- Manufacturer
- Model
- Fuel type
- Fuel cost after 6000 miles

## Technologies Used

- Python: Programming language used for data processing and model development
- Pandas: Data manipulation and preprocessing
- Matplotlib: Data visualization
- Scikit-learn: Machine learning models for regression and clustering
- Jupyter Notebooks: For interactive analysis and code execution

## Project Structure

- `car_fuel_emissions_analysis.ipynb`: Main analysis notebook containing code for data visualization, regression, and clustering.
- `CarFuelandEmissions2000_2013.csv`: The dataset used in this analysis.
- `README.md`: This file, providing an overview of the project.
