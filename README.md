# Anomaly Detection Project

## Overview

This project detects anomalies in transactional data using deep learning techniques, specifically autoencoders. The dataset is dynamically downloaded during runtime to ensure the repository remains lightweight.

## Dataset

- **Name**: Credit Card Fraud Detection
- **Source**: [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Download Method**: Handled programmatically using `kagglehub`.

## Tools and Libraries

This project utilizes the following libraries:

- **Data Manipulation and Processing**:
  - `numpy`
  - `pandas`
- **Visualization**:
  - `matplotlib`
  - `seaborn`
- **Preprocessing and Metrics**:
  - `scikit-learn`
  - `imbalanced-learn`
- **Deep Learning**:
  - `tensorflow`
- **Advanced Modeling**:
  - `xgboost`
  - `optuna`
- **Dataset Handling**:
  - `kagglehub`

## Requirements

Install all required dependencies using:

```bash
pip install -r requirements.txt
```

## Running the Project

```bash
# Step 1: Clone the repository
git clone https://github.com/<username>/Anomaly-detection-project.git
cd Anomaly-detection-project

# Step 2: Install required dependencies
pip install -r requirements.txt

# Step 3: Launch the Jupyter Notebook
jupyter notebook Anomaly_Detection.ipynb

# Step 4: Execute the cells sequentially to reproduce results
```
