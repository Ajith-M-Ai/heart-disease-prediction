# Heart Disease Prediction

## Project Overview
This project aims to predict the likelihood of heart disease in patients using machine learning techniques applied to clinical and demographic data. Early prediction can help healthcare professionals take preventive actions and reduce life-threatening risks.

---

## Problem Statement
Cardiovascular diseases are one of the leading causes of death worldwide. The objective of this project is to build a machine learning model that can predict whether a person is likely to have heart disease based on medical attributes such as age, blood pressure, cholesterol levels, heart rate, and other clinical factors.

---

## Dataset
- Medical dataset containing patient clinical and demographic information  
- Each record represents a patient  
- The dataset includes features such as:
  - Age and sex
  - Chest pain type
  - Resting blood pressure
  - Serum cholesterol
  - Maximum heart rate achieved
  - Exercise-induced angina
  - Electrocardiographic results

### Target Variable
- `1` → Presence of heart disease  
- `0` → No heart disease  

---

## Exploratory Data Analysis (EDA)
- Checked dataset shape, data types, and missing values  
- Analyzed distributions of numerical features  
- Studied relationships between clinical attributes and heart disease outcome  
- Identified important features contributing to heart disease risk  

---

## Data Preprocessing
- Handled missing or inconsistent values  
- Encoded categorical variables where required  
- Scaled numerical features to bring them to a common range  
- Split data into training and testing sets  

---

## Machine Learning Models
The following classification models were trained and evaluated:
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Random Forest Classifier  

---

## Model Evaluation
Models were evaluated using standard classification metrics:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

The best-performing model was selected based on balanced performance across these metrics.

---

## Results
The selected model successfully predicts the presence of heart disease with reliable performance. The results demonstrate that machine learning can assist in identifying high-risk patients at an early stage.

---

## Challenges Faced
- Correlation among medical features  
- Selecting appropriate models for healthcare data  
- Balancing model performance and interpretability  

These challenges were addressed through careful preprocessing, model comparison, and evaluation.

---

## Conclusion
This project demonstrates an end-to-end machine learning workflow for heart disease prediction using clinical data. The model can support healthcare professionals in early diagnosis and preventive decision-making.

---

## Author
**Ajith M**  
Aspiring AI/ML Engineer
