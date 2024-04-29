# Predictive Analytics for Healthcare: Patient Readmission Prediction

## Project Overview

This project aims to develop robust machine learning models to predict the likelihood of patient readmissions within hospitals. Focusing on diabetic patients, this initiative seeks to improve healthcare outcomes and operational efficiencies by utilizing predictive analytics. The models developed in this project are crafted entirely from the ground up, employing various machine learning techniques tailored to the unique challenges of healthcare data.

## Team Members

- Nithin Rajulapati
- Lalitha Velagapudi

## Mentor

- Prof. Stephen Avsec

## Dataset

The data used in this project was sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008), specifically the "Diabetes 130-US hospitals for years 1999-2008" dataset.

## Models Developed

- Logistic Regression
- Decision Trees
- Support Vector Machines (SVM)
- Artificial Neural Networks
- Random Forest (with a focus on improving the recall metric)

## Key Features

- Extensive data preprocessing and feature engineering to handle the nuances of healthcare data.
- Emphasis on recall to capture the majority of true readmissions, crucial for patient care.
- Ensemble techniques to improve model stability and performance.
- Advanced feature design including patient demographics, medical history, and treatment profiles.

## Performance

The best-performing model, Random Forest, achieved a recall score greater than 0.73, indicating its effectiveness in identifying patients at high risk of readmission.

## Repository Contents

- `Patient_Readmission_Prediction.ipynb`: Jupyter notebook containing all the code and documentation for the models.
- `data/`: Folder containing the datasets used.
- `models/`: Folder containing saved models and their checkpoints.

## Installation and Running

```bash
git clone [https://github.com/your-github-username/patient-readmission-prediction.git](https://github.com/Nani1-glitch/CS-584-ML-Project)
cd patient-readmission-prediction
pip install -r requirements.txt
