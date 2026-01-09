
Project Title

# ICU Mortality Prediction Using Machine Learning

# Problem Statement

Intensive Care Units (ICUs) handle critically ill patients where early prediction of mortality risk is crucial for effective clinical decision-making. However, manual assessment based on multiple physiological parameters is time-consuming and error-prone. There is a need for an automated system that can analyze patient clinical data and accurately predict ICU mortality risk.

# Objective

The main objectives of this project are:

To analyze ICU patient clinical data

To derive an ICU mortality label using validated severity scores

To build machine learning models for ICU mortality prediction

To evaluate and compare model performance using standard metrics

# Dataset Description

Dataset Type: ICU clinical data

Number of Records: 3600 patients

Number of Features: 120 clinical attributes

# Key Features:

Demographics: Age, Gender, Height, Weight

Vital Signs: Heart rate, Blood pressure, Respiratory rate, Temperature

Lab Results: Glucose, Creatinine, Lactate, WBC, Platelets

Severity Scores: SAPS-I, SOFA

⚠ The dataset does not contain a direct mortality label.
ICU mortality is derived using the SOFA score, a clinically validated severity scoring system.

# Mortality Rule Used:

SOFA ≥ 11 → High mortality risk (1)

SOFA < 11 → Low mortality risk (0)

# Methodology / Approach

Load ICU clinical dataset

Clean and preprocess data

Handle missing values using median imputation

Derive mortality label from SOFA score

Normalize features using standard scaling

Split dataset into training and testing sets

# Train machine learning models:

Logistic Regression

Random Forest

Evaluate models using accuracy, ROC-AUC, precision, recall, and F1-score

Predict ICU mortality risk

Tools & Technologies Used

Programming Language: Python

Development Environment: Google Colab

# Libraries:

Pandas

NumPy

Scikit-learn

# Machine Learning Models:

Logistic Regression

Random Forest Classifier

# Steps to Run the Project

Open Google Colab

Upload the dataset file icu.csv

Open the Python notebook or script

Run all cells sequentially

View model performance and predictions in the output

# Results / Output

Random Forest achieved higher accuracy and ROC-AUC compared to Logistic Regression

The model successfully classifies patients into:

High ICU mortality risk

Low ICU mortality risk

The system can assist clinicians in early risk assessment

# Dataset

File Name: icu.csv

Source: ICU clinical dataset (academic use)

If file size is large, upload via Google Drive and provide link

# Trained Model Files

Models are trained during runtime

No pre-saved model files included

Models can be saved using joblib if required
