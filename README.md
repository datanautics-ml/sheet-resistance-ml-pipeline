# README.md
# Sheet Resistance Prediction ML Pipeline

A comprehensive machine learning pipeline for predicting sheet resistance in POCl3 doping process using data from Seungtae Lee *et al*. [Paper](https://www.sciencedirect.com/science/article/abs/pii/S1369800125004962) and [Repository](https://github.com/KU-Seungtae/POCl3_ML). This showcases modern MLOps practices including data versioning, feature stores, experiment tracking, and model explainability.

## Project Overview

This project demonstrates an end-to-end ML pipeline that:
- Extracts data from the original data source
- Implements data quality validation and versioning
- Uses a feature store for consistent feature management
- Trains a regression model for sheet resistance prediction
- Provides model explainability with SHAP
- Deploys a Streamlit web application for predictions
- Orchestrates everything with Prefect workflows