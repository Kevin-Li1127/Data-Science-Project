# Data-Science-Project

This repository contains the code used in my MSc dissertation project on **streamflow–precipitation elasticity**.  
The notebooks cover data preprocessing, elasticity estimation (GLS2), and machine learning models (RF, XGBoost, Lasso+RF, Lasso+XGBoost) with SHAP-based interpretation.

## Dataset
The data used in this project can be accessed from Zenodo:  
[Streamflow–Precipitation Elasticity Dataset (Zenodo)](https://zenodo.org/records/15349031)

## Repository structure
- `data_clean.ipynb` — data preprocessing and cleaning  
- `gls2.ipynb` — implementation of the GLS2 method for elasticity estimation  
- `gls2_Analysis.ipynb` — detailed analysis and evaluation of GLS2 elasticity results  
- `RF.ipynb` — Random Forest model training and evaluation  
- `XGboost.ipynb` — XGBoost model training and evaluation  
- `Lasso+RF.ipynb` — pipeline combining Lasso feature selection with Random Forest  
- `Lasso+XGboost.ipynb` — pipeline combining Lasso feature selection with XGBoost  
- `global_elasticity_analysis.ipynb` — global-scale elasticity analysis and visualisation  

## Requirements
The code was developed in Python 3.9 with the following libraries:
- numpy, pandas, geopandas, matplotlib
- statsmodels (GLSAR)
- scikit-learn
- xgboost
- shap

## Usage
Clone the repository and run the notebooks in Jupyter:

```bash
git clone https://github.com/Kevin-Li1127/Data-Science-Project.git
cd Data-Science-Project
jupyter notebook
