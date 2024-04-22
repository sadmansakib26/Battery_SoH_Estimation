# Battery SoH Prediction

This repository contains the code for my undergraduate thesis titled "Enhancing Battery State of Health Estimation using Machine Learning Techniques". 

## Project Overview

The project aims to estimate the State of Health of batteries using ensemble models. The project uses two datasets, `Nasa` and `Calce`, and four different regressors: `Random Forest`, `XGBoost`, `LightGBM`, and `Catboost`.

## Datasets

The `Nasa` and `Calce` folders under `Data & Outputs` contain the datasets used in this project. Each folder contains processed CSV files and raw data files.

- Nasa Dataset: [Link](https://www.nasa.gov/intelligent-systems-division/discovery-and-systems-health/pcoe/pcoe-data-set-repository/)
- Calce Dataset: [Link](https://github.com/konkon3249/BatteryLifePrediction/tree/master)

## Methodology

The project follows these steps:

1. **Exploratory Data Analysis (EDA)**: Understanding the data by visualizing it.
2. **Feature Engineering & Prerprocessing**: Creating Features and Data preprocessing for later use.
2. **Feature Selection**: Selecting the most relevant features for the predictive model. 
3. **Modeling**: Training predictive models to predict customer churn.
4. **Hyperparameter Tuning**: Optimizing the model hyperparameters for better performance. 

## Project Structure

- `Scripts/`: Contains the main codes for the project.
- `Data & Outputs/`: Stores both the processed and original datasets, and outputs.

## Scripts

The `Scripts` folder contains Jupyter notebooks for different stages of the project:

- `EDA_FE_Preprocessing.ipynb`: Exploratory Data Analysis and Feature Engineering
- `Feature_Selection.ipynb`: Feature Selection
- `Hyperparameter_Optimization.ipynb`: Hyperparameter Tuning
- `Performance_Evaluation.ipynb`: Model Performance Evaluation
- `Plot_Predictions.ipynb`: Plotting Predictions

## Usage

To run the project, follow these steps:

1. Clone the repository.
2. Install the required dependencies.
3. Run the .ipynb files in the `Scripts/` directory in the following order:
(i) EDA_FE_Preprocessing.ipynb, (ii) Feature_Selection.ipynb, (iii) Hyperparameter_Optimization.ipynb, (iv) Performance_Evalutaion.ipynb.ipynb, (v) Plot_Predictions.ipynb.

## Contact

For any queries, please reach out at [sadmansakib26@iut-dhaka.edu](sadmansakib26@iut-dhaka.edu).
