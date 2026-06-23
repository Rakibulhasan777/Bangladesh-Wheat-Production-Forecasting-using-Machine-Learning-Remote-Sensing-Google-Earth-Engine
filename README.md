# Bangladesh Wheat Production Forecasting using Machine Learning, Remote Sensing & Google Earth Engine
## Project Overview
Developed an end-to-end machine learning pipeline to predict district-level wheat production across Bangladesh by integrating official agricultural statistics with satellite-derived environmental indicators. The project combines agricultural economics, remote sensing, geospatial analytics, and predictive modeling to generate production forecasts and identify the key factors influencing wheat yields. 

## Problem Statement
Accurate crop production forecasting is essential for food security planning, agricultural policy development, and resource allocation. This project aims to predict wheat production at the district level using historical production records and satellite-derived climatic and vegetation indicators extracted from Google Earth Engine (GEE). 

## Data Sources
#### Agricultural Data
- Bangladesh Bureau of Statistics (BBS) wheat production data
- District-level harvested area and production records
- Crop years: 2014–15 to 2023–24
#### Remote Sensing and Climate Data
Satellite-derived covariates extracted through Google Earth Engine:
- CHIRPS Rainfall
- MODIS NDVI (Normalized Difference Vegetation Index)
- MODIS EVI (Enhanced Vegetation Index)
- MODIS Land Surface Temperature (Day & Night)
- Additional environmental and climatic indicators

## Methodology
#### Data Preprocessing
- Merged multi-source datasets at district level
- Performed missing value treatment and outlier detection
- Conducted feature engineering and variable transformation
- Created a reproducible data processing workflow

#### Machine Learning Pipeline
- Implemented supervised regression models for wheat production prediction
- Applied K-Fold Cross-Validation for robust model evaluation
- Evaluated performance using:R² Score, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE)
#### Model Interpretation
- Performed feature importance analysis
- Applied SHAP (SHapley Additive Explanations) to interpret model predictions
- Identified the most influential climatic and vegetation variables affecting wheat production
#### Forecasting
- Generated district-level wheat production forecasts for an out-of-sample crop year
- Compared historical production patterns with predicted values
#### Geospatial Visualization
- Developed an interactive HTML choropleth map
- Visualized district-level production forecasts
- Enabled hover-based exploration of forecast values and district information
#### Key Deliverables
- Reproducible machine learning workflow
- Wheat production prediction model
- District-level production forecasts
- SHAP-based model interpretation
- Interactive geospatial forecast dashboard
- Google Earth Engine data extraction scripts
## Technologies Used
#### Programming & Data Science
- Python
- Pandas
- NumPy
- Scikit-learn
#### Machine Learning
- Regression Modeling
- Cross-Validation
- Feature Engineering
- Model Evaluation
#### Explainable AI
- SHAP
- Feature Importance Analysis
#### Geospatial Analytics
- Google Earth Engine (GEE)
- GeoPandas
- Folium
- Interactive Choropleth Mapping
#### Data Visualization
- Matplotlib
- Seaborn
- Plotly
#### Skills Demonstrated
- Machine Learning
- Predictive Analytics
- Agricultural Data Analysis
- Remote Sensing Analytics
- Geospatial Data Processing
- Feature Engineering
- Explainable AI (XAI)
- Forecasting
- Data Cleaning and Preprocessing
- Cross-Validation and Model Evaluation
- Interactive Geospatial Visualization
- Reproducible Research Workflow Development
## Project Impact
This project demonstrates how satellite remote sensing data and machine learning can be integrated to support agricultural decision-making, crop monitoring, and food security planning. The workflow can be extended to other crops, regions, and agricultural forecasting applications.
