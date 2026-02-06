# Insurance Claim Prediction

## Project Overview
This project builds a machine learning model to predict the probability that a building
will have at least one insurance claim during an insured period based on building
characteristics.

## Dataset
The dataset contains building-level information such as building size, location,
construction attributes, and insured period details. The target variable `Claim` is
binary:
- 1: At least one claim occurred
- 0: No claim occurred

## Project Structure
The project is organized into three main notebooks:
- **01_eda.ipynb** – Exploratory Data Analysis and initial insights
- **02_preprocessing.ipynb** – Data cleaning, feature engineering, and preprocessing
- **03_modeling.ipynb** – Model training, evaluation, and comparison

## Models Used
- Logistic Regression
- Random Forest
- XGBoost Classifier

## Evaluation
Models were evaluated using accuracy, precision, recall, F1-score, ROC curves, and
confusion matrices. Due to class imbalance, recall and F1-score were considered
important evaluation metrics.

## Conclusion
XGBoost provided the best overall performance, offering a reasonable trade-off between
precision and recall after threshold adjustment.

## Author
Daniel Omotoye

