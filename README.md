# Network Traffic Classification using KNN

## Project Overview
This project focuses on **classifying network traffic** into different connection statuses (e.g., *success* / *fail*) using machine learning techniques.

The goal is to build a simple intrusion detection / network monitoring model based on structured network data.

---

## Objectives
- Perform **data exploration and cleaning**
- Apply **data preprocessing and transformation**
- Train a **K-Nearest Neighbors (KNN)** classification model
- Evaluate model performance using standard metrics

  
---

## Technologies Used
- Python 
- Pandas
- Matplotlib / Seaborn
- Scikit-learn

---

## Workflow

1. **Data Collection**
   - Load raw dataset from `data/raw/`

2. **EDA & Cleaning**
   - Handle missing values
   - Remove irrelevant features

3. **Preprocessing**
   - Feature scaling (MinMaxScaler)
   - Data transformation

4. **Model Training**
   - Train KNN model with different values of *k*

5. **Evaluation**
   - Accuracy score
   - Classification report
   - Confusion matrix

---

## Model Performance

- Tested with multiple values of **K (3, 5, 7)**


