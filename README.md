# Parkinson’s Disease Detection Using Machine Learning

- [Visit Project](https://colab.research.google.com/drive/1t5R9saa0o4-9kmJ7KRNF1Ygv1fG9fTpN?usp=sharing)
- [Reference](https://archive.ics.uci.edu/dataset/174/parkinsons)

## Project Overview
This project implements a supervised machine learning system to detect Parkinson’s Disease using biomedical voice measurements. The system analyzes voice-related features and classifies individuals as either healthy or affected by Parkinson’s disease.

The model is developed using Python and executed in Google Colab. Support Vector Machine (SVM) is used as the primary classification algorithm due to its effectiveness in medical diagnostic tasks.

---

## Objectives
- To analyze and preprocess Parkinson’s disease data
- To apply feature scaling for improved model performance
- To train a machine learning classifier for disease detection
- To evaluate the model using standard performance metrics

---

## Dataset Information
- Format: CSV
- File Name: Parkinson.csv
- Total Samples: 195
- Number of Features: 22
- Target Variable: `status`
  - 0 → Healthy
  - 1 → Parkinson’s Disease

The dataset consists of biomedical voice measurements collected from both healthy individuals and Parkinson’s patients.

---

## Tools and Technologies
- Programming Language: Python
- Platform: Google Colab
- Libraries Used:
  - Pandas
  - NumPy
  - Scikit-learn
- Machine Learning Algorithm:
  - Support Vector Machine (SVM)

---

## Methodology
1. Load the dataset from Google Drive
2. Remove unnecessary columns (e.g., patient name)
3. Split the dataset into training and testing sets
4. Apply feature scaling using StandardScaler
5. Train the SVM classifier
6. Evaluate performance using accuracy, precision, recall, F1-score, and confusion matrix

