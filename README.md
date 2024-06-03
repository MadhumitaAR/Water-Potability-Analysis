**Water Potability Analysis using Logistic Regression**
This repository contains a project for analyzing water potability using data analysis and machine learning techniques, specifically logistic regression. The aim is to predict whether a given water sample is safe for drinking based on various water quality parameters.

Introduction
Water potability analysis is essential for ensuring safe drinking water. This project uses logistic regression to predict water potability based on parameters such as pH, hardness, total dissolved solids (TDS), chlorides, sulfates, conductivity, turbidity, and microbiological contaminants.

Dataset
The dataset used in this project contains various water quality parameters and the potability status (potable or not potable). You can find the dataset here. 
https://www.kaggle.com/datasets/uom190346a/water-quality-and-potability?resource=download


water-potability-analysis/
│
├── data/
│   ├── raw/                # Raw data files
│   ├── processed/          # Processed data files
│
├── notebooks/              # Jupyter notebooks for exploration and analysis
│
├── src/
│   ├── Water_Potability_Analysis  # Data cleaning, preprocessing, finding outliers, EDA, Logistic regression model, evaluation and prediction.
              
│
├── tests/                  # Test scripts
│
├── README.md               # Project README
└── requirements.txt        # Python packages requirements


Model Training
The logistic regression model is trained on the processed dataset. This model includes data splitting, model fitting, and evaluation using various metrics.



