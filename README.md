# House Price Prediction with MLflow

This project demonstrates how to train a machine learning model for house price prediction, tune its hyperparameters, and log the results using MLflow for easy comparison and model management.

## Overview

### Steps in the Process:
1. **Data Preparation**:
   - Use the California housing dataset.
   - Create a DataFrame with features and the target (house prices).

2. **Train-Test Split**:
   - Split the data into training and test sets (80% train, 20% test).

3. **Hyperparameter Tuning**:
   - Perform hyperparameter tuning using `GridSearchCV` to find the best model parameters.

4. **MLflow Logging**:
   - Log hyperparameters, metrics (e.g., Mean Squared Error), and model performance to the MLflow UI.
   - Compare the results of different runs in MLflow and register the best model.

## How to Run

- **Start the MLflow server**: Run `mlflow ui` in your terminal.  
  This will open the MLflow UI at `http://127.0.0.1:5000`.

- **Run the script**:
   1. Execute the script to start hyperparameter tuning.
   2. Log the results to MLflow and compare different runs in the MLflow UI.

### Output 
![alt text](image.png)
![alt text](image-1.png)