[README.md](https://github.com/user-attachments/files/27410426/README.md)
# Cirrhosis Patient Outcome Prediction via Neural Network

**Course:** Foundations of Data Science  
**Institution:** Del Mar College  
**Date:** May 2026

## Overview

This project applies supervised machine learning to predict patient survival outcomes using the Mayo Clinic primary biliary cirrhosis (PBC) dataset. A binary classification neural network was built in TensorFlow using standard clinical measurements including lab values, demographic data, and disease-stage indicators.

## Dataset

- **Source:** OpenStax Principles of Data Science companion materials
- **Original records:** 418 patients from the Mayo Clinic PBC trial (1974-1984)
- **After cleaning:** 276 complete records used for training and testing

## Methodology

- Dropped rows with missing values using `dropna()`
- Removed non-predictive columns: ID, N_Days, Drug
- One-hot encoded the Edema variable
- Binary mapped Sex, Ascites, Hepatomegaly, and Spiders
- Applied StandardScaler normalization
- 80/20 train/test split with random state 42
- Built a Sequential neural network in TensorFlow Keras with two hidden layers of 16 neurons using ReLU activation and a sigmoid output layer
- Compiled with Adam optimizer and binary cross-entropy loss
- Trained over 10 epochs

## Results

| Metric | Value |
|---|---|
| Final Training Loss | 0.538 |
| Final Training Accuracy | 77.7% |
| Test Accuracy | 80.4% |

## Files

| File | Description |
|---|---|
| `ameyer_cirrhosis.ipynb` | Jupyter notebook with full code and output |
| `ameyer_cirrhosis_report.pdf` | Written research report |
| `AMeyer_Project_A_Cirrhosis.pptx` | Presentation slides |

## Tools Used

Python, TensorFlow, Keras, Pandas, scikit-learn, Jupyter Notebook
