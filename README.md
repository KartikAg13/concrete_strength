# Concrete Strength Prediction

- **Project Overview**
  - Predicts concrete's compressive strength.
  - Uses ensemble methods:
    - RandomForestRegressor.
    - XGBoostRegressor.
  - Combines predictions using a weighted average.

- **File Structure**
  - `main.ipynb` – Jupyter Notebook with code implementation.
  - `LICENSE` – Project license.
  - `readme.md` – Project documentation.

- **Features**
  - Data loading and preprocessing.
  - Train-test split of the dataset.
  - Model training with RandomForest and XGBoost.
  - Prediction evaluation using:
    - Mean Squared Error (MSE).
    - R2 Score.
  - Weighted average of predictions for final output.

- **Requirements**
  - Python 3.x
  - Libraries:
    - numpy
    - pandas
    - matplotlib
    - scikit-learn
    - xgboost

- **Setup Instructions**
  - Clone the repository.
  - Install required packages:
    - `pip install numpy pandas matplotlib scikit-learn xgboost`
  - Open `main.ipynb` using Jupyter Notebook or any compatible IDE.

- **Usage**
  - Run all cells in `main.ipynb` sequentially to:
    - Load the dataset.
    - Train the RandomForest and XGBoost models.
    - Compute predictions and evaluate model performance.
    - Combine predictions using the weighted average.

- **License**
  - Refer to the `LICENSE` file for license details.
