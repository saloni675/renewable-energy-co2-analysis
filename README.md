# Renewable Energy and CO₂ Emissions: A Cross-Country Analysis

## Project Overview

This project investigates the relationship between renewable energy adoption and CO₂ emissions across different countries using real-world sustainability datasets from Our World in Data.

The project combines data collection, database design, SQL analysis, data visualization, and machine learning to identify trends and patterns related to sustainable energy usage.

## Research Question

What is the relationship between renewable energy use and CO₂ emissions across different countries?

## Objectives

* Compare renewable energy share among countries
* Compare CO₂ emission levels among countries
* Analyze trends over multiple years
* Store sustainability data in a relational database
* Perform SQL-based analysis
* Visualize key findings
* Apply machine learning to explore relationships between variables

## Dataset Sources

* Our World in Data (OWID)
* CO₂ Emissions Dataset
* Energy Dataset

## Database Design

The SQLite database contains three tables:

### Countries

* country_id (Primary Key)
* country_name

### RenewableEnergy

* energy_id (Primary Key)
* country_id (Foreign Key)
* year
* renewables_share_energy

### CO2Emissions

* emission_id (Primary Key)
* country_id (Foreign Key)
* year
* co2

## SQL Queries Performed

1. Average Renewable Energy Share by Country
2. Average CO₂ Emissions by Country
3. Renewable Energy and CO₂ Trend Analysis

## Visualizations

* Average Renewable Energy Share by Country
* Average CO₂ Emissions by Country
* Renewable Energy vs CO₂ Scatter Plot
* Trend Analysis Graphs

## Machine Learning

A Linear Regression model was applied to study the relationship between renewable energy share and CO₂ emissions.

### Model Results

* MAE: 2762.73
* MSE: 12736306.19
* R² Score: 0.0062

The low R² score indicates that renewable energy share alone is not sufficient to accurately predict CO₂ emissions. Additional factors such as population, industrial activity, GDP, and energy consumption would improve the model.

## ER Diagram

The project database follows a relational structure connecting countries, renewable energy data, and CO₂ emission data.

## Key Findings

* Countries with higher renewable energy adoption often show lower emission levels.
* Renewable energy contributes to sustainability goals but is not the only factor affecting emissions.
* The relationship between renewable energy and CO₂ emissions is complex and influenced by multiple economic and environmental variables.

## Future Improvements

* Include more countries and years
* Add GDP and population indicators
* Build advanced machine learning models
* Create an interactive dashboard using Power BI or Tableau

## Technologies Used

* Python
* Pandas
* SQLite
* SQL
* Matplotlib
* Scikit-Learn
* Jupyter Notebook
* VS Code

## Author

Saloni Kaushik
