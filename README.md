# 🫀 Heart Disease Prediction System

## 📌 Overview
This project predicts the likelihood of a person having heart disease using machine learning techniques.  
It applies supervised learning algorithms to a clinical dataset and builds an interpretable model that can assist in early medical diagnosis.

---

## 🎯 Objectives
- Analyze medical data to identify key risk factors for heart disease.  
- Build and evaluate predictive ML models.  
- Compare model performance and interpret results for practical healthcare use.

---

## 🧠 Algorithms Used
- Logistic Regression  
- Support Vector Machine (SVM)  
- Random Forest Classifier  

---

## 🧰 Technologies & Tools
- **Programming Language:** Python  
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn  
- **Environment:** Google Colab / Jupyter Notebook  

---

## 🧩 Dataset
- **Source:** [UCI Machine Learning Repository – Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease)  
- **Samples:** 303 records  
- **Features:** 13 clinical attributes (age, sex, cholesterol, blood pressure, chest pain, etc.)  
- **Target:**  
  - `1` → Patient has heart disease  
  - `0` → No heart disease  

---

## ⚙️ Steps in Implementation
1. **Data Loading & Exploration**
   - Import dataset and analyze missing/null values.
2. **Data Preprocessing**
   - Handle categorical values using *one-hot encoding*.  
   - Normalize numerical features with *StandardScaler*.
3. **Exploratory Data Analysis**
   - Visualize relationships using histograms, heatmaps, and correlation plots.
4. **Model Building**
   - Train models: Logistic Regression, SVM, Random Forest.
5. **Evaluation**
   - Metrics used: Accuracy, Precision, Recall, F1 Score.
6. **Prediction**
   - Test model on new data input.

---

## 📊 Results
- **Best Accuracy:** ~85% (Logistic Regression)  
- **Key Predictive Features**: Chest Pain Type, ST Depression, Number of Vessels, Thalassemia  
- **Insight:** Logistic Regression provided interpretable coefficients useful for clinical understanding.
