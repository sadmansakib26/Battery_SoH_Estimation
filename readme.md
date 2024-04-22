# Battery SoH Prediction

This repository contains the code for my undergraduate thesis. The project aims to estimate the State of Health of batteries using machine learning models. The project uses two datasets, `Nasa` and `Calce`, and four different regressors: `Random Forest`, `XGBoost`, `LightGBM`, and `Catboost`.

## Datasets

The `Nasa` and `Calce` folders under `Data & Outputs` contain the datasets used in this project. Each folder contains processed CSV files and raw data files.

## Scripts

The `Scripts` folder contains Jupyter notebooks for different stages of the project:

- `EDA_FE_Preprocessing.ipynb`: Exploratory Data Analysis and Feature Engineering
- `Feature_Selection.ipynb`: Feature Selection
- `Hyperparameter_Optimization.ipynb`: Hyperparameter Tuning
- `Performance_Evaluation.ipynb`: Model Performance Evaluation
- `Plot_Predictions.ipynb`: Plotting Predictions

## Outputs

The `CAT`, `LGBM`, `RF`, and `XGB` folders under each dataset folder contain the outputs of the corresponding regressor for that dataset.

## Usage

To run the project, follow these steps:

1. Clone the repository.
2. Install the required dependencies.
3. Run the .ipynb files in the `Scripts/` directory in the following order:
(i) EDA_FE_Preprocessing.ipynb, (ii) Feature_Selection.ipynb, (iii) Hyperparameter_Optimization.ipynb, (iv) Performance_Evalutaion.ipynb.ipynb, (v) Plot_Predictions.ipynb.

## Contact

For any queries, please reach out at [sadmansakib26@iut-dhaka.edu](sadmansakib26@iut-dhaka.edu).
