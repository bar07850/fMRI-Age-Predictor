# Brain Age Prediction from fMRI Data

This project builds a complete machine learning pipeline to predict participant age from synthetic fMRI brain connectivity data. It uses advanced data preprocessing, dimensionality reduction (PCA), oversampling of under-represented age groups, and model training with Random Forest, Ridge Regression, and XGBoost regressors.

> **Note**: The dataset is not included in this repository. You must obtain the data through your research files or synthetic dataset provider.

## 💻 Main Features
## 📂 Dataset

The dataset consists of synthetic upper triangular matrix representations of fMRI-derived brain connectivity data.  
To run this notebook, you must have the dataset saved in your Google Drive in the following structure:

## 💻 Main Features

- Data loading from `.tsv` and `.csv` files
- Cleaning and reshaping upper triangular matrices into feature vectors
- Data scaling and dimensionality reduction using PCA
- Oversampling of under-represented age groups
- Model training and tuning using:
    - Random Forest Regressor
    - Ridge Regression
    - XGBoost Regressor
- Model evaluation with RMSE, MAE, and R² metrics
- Visualizations of feature importance and correlations

## 🛠️ Requirements

Recommended Python version: 3.8+

You can install the required packages by creating a `requirements.txt` file with the following content:

