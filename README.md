# Machine Learning Projects — Real-World Classification & Predictive Modeling

[![Language](https://img.shields.io/badge/Language-Python_3-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Notebooks](https://img.shields.io/badge/Environment-Jupyter_Notebooks-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org)
[![Scikit-Learn](https://img.shields.io/badge/ML-Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)

A curated collection of end-to-end machine learning implementations exploring exploratory data analysis (EDA), data cleaning, feature engineering, cross-validation, and classification algorithms.

---

## Projects Included

### 1. Rock vs. Mine Sonar Signal Classification (`Project-1/`)
- **Objective:** Discriminate between sonar signals bounced off metal cylinders (mines) vs. rough rocks using acoustic frequency patterns.
- **Model:** Logistic Regression & Support Vector Classifier (SVC).
- **Techniques:** Standardized feature scaling, train/test stratified split, confusion matrix diagnostics.

### 2. Early Diabetes Diagnosis Prediction (`project-2/`)
- **Objective:** Predict diabetic risk based on diagnostic clinical measurements (glucose, insulin, BMI, age).
- **Model:** Support Vector Machine (SVM) with radial basis kernel (RBF) and Logistic Regression.
- **Metrics:** Precision, recall, ROC-AUC evaluation.

### 3. Indian Air Quality Index (AQI) Time-Series Analysis (`Indian_Air_Quality.ipynb`)
- **Objective:** Analyze particulate matter (PM2.5, PM10), NO2, and SO2 levels across Indian metropolitan regions.
- **Techniques:** Missing value imputation, trend decomposition, pollutant correlation heatmaps.

---

## How to Run Locally

```bash
git clone https://github.com/MuhammadMinhaj229/Machine-Learning-Projects.git
cd Machine-Learning-Projects

python -m venv venv
.\venv\Scripts\activate
pip install numpy pandas scikit-learn matplotlib seaborn jupyter

jupyter notebook
```

---

## Author
**Mohammed Minhaj Mahmood** ([@MuhammadMinhaj229](https://github.com/MuhammadMinhaj229)).
