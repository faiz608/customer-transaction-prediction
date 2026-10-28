# Customer Transaction Prediction

## Project Overview

This project explores customer transaction data using exploratory data analysis (EDA) and machine learning techniques. It uses a CatBoost classification model to predict the target class from customer transaction features.

The project demonstrates data exploration, preprocessing, visualization, model training, and performance evaluation.

## Objectives

* Explore the dataset and understand its structure.
* Analyze the distribution of the target variable.
* Examine missing values and duplicate records.
* Visualize feature distributions and correlations.
* Prepare numerical features for analysis.
* Train a CatBoost classification model.
* Evaluate model performance using classification metrics.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* CatBoost
* Jupyter Notebook

## Project Structure

```text
customer-transaction-prediction/
│
├── customer_transaction.ipynb
├── README.md
└── requirements.txt
```

## Project Workflow

### 1. Data Exploration

* Inspect dataset dimensions and columns.
* Review descriptive statistics.
* Check missing values and duplicate records.
* Examine target class distribution.

### 2. Exploratory Data Analysis

* Visualize the target distribution.
* Plot numerical feature distributions.
* Explore correlations between features.

### 3. Data Preprocessing

* Separate input features from the target.
* Exclude the identifier column from model inputs.
* Split the data into training and testing sets.
* Apply numerical imputation during exploratory preprocessing.

### 4. Model Building

* Train a CatBoost classifier.
* Configure model parameters, including iterations, learning rate, and tree depth.

### 5. Model Evaluation

* Evaluate predictions using accuracy.
* Calculate ROC-AUC.
* Review the classification report.

## Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open `customer_transaction.ipynb` to explore the analysis and model.

## Dataset

The notebook expects a dataset file named `train(1).csv`.

Place the dataset in the appropriate working directory before running the notebook. If the dataset cannot be redistributed, obtain it from its original source and follow the source's access and licensing requirements.

## Results

The notebook contains the model training and evaluation code. Refer to the executed notebook for the actual evaluation results.

## Future Improvements

* Compare CatBoost with additional classification algorithms.
* Improve hyperparameter tuning.
* Analyze feature importance.
* Investigate class imbalance and appropriate evaluation metrics.
* Validate the model on an independent test set.

## Author

Faizan Ali
