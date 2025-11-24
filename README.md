# Wastewater-Influenza-A-Analysis

A comprehensive analysis of Influenza A detection in wastewater. Data cleaning, feature engineering, exploratory data analysis (EDA), and machine learning models have been applied using Python. 

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Features](#features)
- [Machine Learning Models](#machine-learning-models)
- [Visualizations](#visualizations)
- [License](#license)

## Overview
This project aims to analyze Influenza A viral concentrations in wastewater. The main objectives are:
- Clean and preprocess raw data
- Perform feature engineering to create meaningful variables
- Conduct exploratory data analysis (EDA)
- Apply feature selection and dimension reduction techniques
- Train and evaluate machine learning models for Influenza A detection

## Project Structure
wastewater-project/

├─ data/ # Raw dataset

└─ CDC_Wastewater_Data_for_Influenza_A.csv

├─ notebooks/ # Jupyter notebooks

└─ wastewater-influenza-a-analysis.ipynb

├─ .gitignore

└─ README.md

## Installation

1. Clone this repository:

```bash
git clone https://github.com/silakbpc/wastewater-influenza-a-analysis.git
``` 
2. Create a virtual environment and activate it:
   
```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
```

3. Install required packages:
```bash
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
pip install scikit-learn
```

## Usage
Open the Jupyter notebook and run cells step by step:
jupyter notebook notebooks/wastewater-influenza-a-analysis.ipynb
The notebook performs:
Data cleaning
Feature engineering
Exploratory data analysis (EDA)
Feature selection
Dimension reduction
Machine learning modeling and evaluation

## Data
The raw dataset CDC_Wastewater_Data_for_Influenza_A.csv is stored in the data/ folder.
Note: If the cleaned dataset is generated within the notebook, it does not need to be stored in the repository.
## Features
Sample collection date: converted to month, week, and day of the week
Flow rate handling and log transformation
Viral RNA concentration and log transformation
Population served and derived features
Rolling averages and standard deviations for trends
Categorized population group with encoding
Polynomial features for modeling

## Machine Learning Models
Logistic Regression
K-Nearest Neighbors (KNN)
Feature selection methods: SelectKBest, RFE, SelectFromModel
Dimension reduction methods: PCA, LDA
Model evaluation metrics: Accuracy, ROC AUC, Precision-Recall, Confusion Matrix

## Visualizations
Weekly trends of viral RNA concentration
Violin plots of viral RNA by population group
ROC curves and precision-recall curves for best models
Feature importance and selection results
License
This project is licensed under the MIT License.
