# Urban Neighborhood Pressure in NYC

## Overview

This project applies the CRISP-DM framework to identify New York City neighborhoods experiencing high urban pressure. Urban pressure is defined as combined stress from housing instability, housing-condition problems, socioeconomic vulnerability, and short-term rental activity.

The analysis integrates Airbnb listings, residential evictions, HPD housing complaints, HPD housing-code violations, ACS socioeconomic indicators, and NYC Neighborhood Tabulation Area boundaries.

## Business Question

Can we identify NYC neighborhoods experiencing high urban pressure using Airbnb activity, residential evictions, HPD housing complaints, HPD housing-code violations, and ACS socioeconomic indicators?

## Methods

The project follows the CRISP-DM process:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation

Main methods include:

- Data cleaning and preprocessing
- Feature engineering
- Geospatial joining with NTA boundaries
- Composite Urban Pressure Score construction
- K-means clustering
- Logistic Regression and Random Forest classification
- Folium choropleth and cluster mapping

## Key Outputs

- Urban Pressure Score
- High-pressure neighborhood ranking
- K-means pressure profiles
- Classification model comparison
- Interactive Folium choropleth map
- Interactive Folium cluster map
- Static charts and evaluation outputs

## Data Access

Large raw data files are not committed directly to this repository. The raw data snapshot used in the project is provided as a GitHub Release asset named `data.zip`.
https://github.com/parsaseyedi/NYC_Urban_Pressure/releases/download/v1.0-data/data.zip

After downloading, extract `data.zip` into the project root so that the folder structure becomes:
```text
NYC_Urban_Pressure/
                  -data          
                  -figures
                  -outputs
                  -NYC_Urban_Pressure.ipynb
