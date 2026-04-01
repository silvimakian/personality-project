# Personality Prediction using Machine Learning

## Overview
This project builds a machine learning model to classify individuals as **Introverts** or **Extroverts** using behavioral and lifestyle features.  
It demonstrates a complete **end-to-end data science workflow** including exploratory data analysis, preprocessing, model training, evaluation, and comparison.

---

## Dataset

The dataset contains behavioral indicators such as:

- Time spent alone  
- Social event attendance  
- Friends circle size  
- Online posting frequency  
- Stage fear  
- Going outside frequency  
- Feeling drained after socializing  

Target variable:
- **Personality** (Introvert / Extrovert)

---

## Exploratory Data Analysis

EDA revealed clear behavioral differences between personality types:

- Introverts attend fewer social events  
- Extroverts have larger friend circles  
- Introverts spend more time alone  
- Stage fear correlates with introversion  
- Extroverts cluster around higher social activity  

Visualizations created:
- Personality distribution pie chart  
- Histograms  
- Scatter plots  
- Bar plots  
- Correlation heatmap  

---

## Data Preprocessing

Steps performed:

- Removed duplicate values  
- Checked for missing values (none found)  
- Encoded categorical features  
- Train-test split (80/20)  
- Feature scaling for KNN and SVM  

---

## Models Used

The following machine learning models were trained and compared:

- Logistic Regression  
- Random Forest Classifier  
- Decision Tree Classifier  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVC)  

Evaluation metrics:
- Accuracy score  
- Confusion matrix  
- Model comparison visualization  

---

## Key Insights

- Introverts tend to feel drained after social interaction  
- Extroverts attend more social events  
- Stage fear strongly correlates with introversion  
- Social activity is the strongest predictor of personality  
- Behavioral features show clear clustering  

---

## Best Model

Although the Decision Tree slightly outperformed others, the **Random Forest Classifier** is the best model for deployment because it provides:

- Better generalization  
- Higher stability  
- Lower overfitting risk  
- Feature importance interpretability  

---

## Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📂 Project Structure
