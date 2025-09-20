# K-Fold Cross-Validation Project

## Project Overview

This repository contains a Jupyter notebook demonstrating the use of k-fold cross-validation to evaluate and compare the performance of different machine learning classifiers.

The notebook uses the popular `digits` dataset from `sklearn` and applies the following models:
- Logistic Regression
- Support Vector Machine (SVC)
- Random Forest Classifier

The `cross_val_score` function is utilized to perform k-fold cross-validation and obtain a robust estimate of each model's accuracy.

## Files in this Repository

- `K fold.ipynb`: The main Jupyter notebook with all the code and analysis.

## How to Run the Notebook

To run this notebook locally, you need to have Python and the necessary libraries installed.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/YourRepositoryName.git](https://github.com/YourUsername/YourRepositoryName.git)
    ```
2.  **Install dependencies:**
    The notebook requires `numpy` and `scikit-learn`. You can install them using pip:
    ```bash
    pip install scikit-learn numpy
    ```
3.  **Open the notebook:**
    Navigate to the project directory and start a Jupyter server:
    ```bash
    jupyter notebook "K fold.ipynb"
    ```
