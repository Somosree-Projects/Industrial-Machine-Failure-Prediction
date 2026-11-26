# Industrial Machine Failure Prediction Using Machine Learning

## Project Overview

This project focuses on predicting machine failures using Machine Learning techniques. It uses the AI4I 2020 Predictive Maintenance Dataset to identify whether a machine is likely to fail based on its operating conditions.

The main objective is to help identify potential machine failures and support predictive maintenance.

## Dataset

- Dataset: AI4I 2020 Predictive Maintenance Dataset
- Total Records: 10,000
- Total Features: 14
- Target Variable: Machine failure

Dataset source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset)

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## Machine Learning Algorithms

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

## Project Workflow

1. Dataset Loading and Exploration
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis
4. Feature Encoding
5. Train-Test Splitting
6. Model Training
7. Model Evaluation
8. 5-Fold Cross-Validation
9. Hyperparameter Tuning using GridSearchCV
10. Best Model Selection
11. Model Saving
12. Machine Failure Prediction

## Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Cross-Validation

## Project Files

- `Industrial_Machine_Failure_Prediction.ipynb` – Complete project implementation.
- `ai4i2020.csv` – Dataset.
- `machine_failure_model.pkl` – Trained machine learning model.
- `requirements.txt` – Required Python libraries.

## How to Run

1. Clone this repository.
2. Open the notebook using Google Colab.
3. Upload the AI4I 2020 dataset when prompted.
4. Run all notebook cells sequentially.
5. Train the models and evaluate their performance.
6. Use the prediction function to predict machine failure for new machine inputs.

## Author

MCA Student | Machine Learning Project
