# Diabetes Risk Prediction

A machine learning system that predicts whether a patient is at risk of developing diabetes based on their medical records.

## What This Project Does

This project analyzes patient data (like glucose levels, BMI, age) and predicts if they might develop diabetes. It's designed to help doctors with early detection.

## Features

- Cleans and prepares medical data
- Trains a smart prediction model  
- Tests accuracy on real patient data
- Predicts risk for new patients
- Shows which factors matter most (like glucose levels)

## Technologies Used

- Python - Main programming language
- Pandas - For handling data
- Scikit-learn - For machine learning
- Random Forest - The prediction algorithm

## How to Use

### Method 1: Jupyter Notebook (Recommended)
1. Download diabetes_prediction.ipynb and diabetes.csv
2. Open the notebook in Jupyter
3. Set the correct dataset path in the code:
   df = pd.read_csv('your/path/to/diabetes.csv')
4. Run each cell step by step

### Method 2: Python Script
1. Copy the code into a Python file
2. Install required packages:
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
3. Set the dataset path in your code
4. Run the Python file
