# Intelligent-crop-recommendation-system

#  Intelligent Crop Recommendation System

##  Project Overview
This project implements an intelligent crop recommendation system using machine learning to suggest suitable crops based on soil nutrients and climatic conditions. The system analyzes parameters such as Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH, and rainfall to support data-driven agricultural decision-making.

---

## Objectives
- Perform exploratory data analysis (EDA) on agricultural data  
- Build and compare multiple machine learning models  
- Identify the best performing model for crop prediction  
- Optimize model performance using hyperparameter tuning  
- Recommend the **top 3 suitable crops with confidence scores**

---

##  Dataset Information
- **Dataset Name:** Crop Recommendation Dataset  
- **Total Records:** 2200  
- **Features:**
  - N (Nitrogen)
  - P (Phosphorus)
  - K (Potassium)
  - Temperature
  - Humidity
  - pH
  - Rainfall  
- **Target Variable:** Crop label

---

##  Exploratory Data Analysis (EDA)
- Checked for missing and duplicate values  
- Analyzed feature distributions  
- Studied relationships between soil parameters and crop types  
- Visualized correlations and patterns affecting crop growth  

---

## Machine Learning Models Used
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Naive Bayes  
- Support Vector Machine (SVM)  

All models were trained using the same train-test split for fair comparison.

---

## Model Evaluation
- Models evaluated using accuracy on test data  
- **Random Forest** achieved the highest accuracy  
- Confusion matrix and classification report used for performance analysis  

---

## ⚙️ Hyperparameter Tuning
- Applied **GridSearchCV** to Random Forest  
- Optimized parameters:
  - Number of trees
  - Maximum depth
  - Minimum samples split
  - Minimum samples per leaf  
- Improved model generalization and stability  

---

##  Top-3 Crop Recommendation System
Instead of predicting a single crop, the system recommends the **top three most suitable crops** along with confidence scores, transforming the model into a practical agricultural decision support system.

---

##  Technologies Used
- **Programming Language:** Python  
- **Libraries:**  
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  

---

##  Results
- High prediction accuracy across multiple models  
- Tuned Random Forest delivered the best performance  
- Feature importance analysis identified key factors influencing crop selection  

---

##  Future Scope
- Integration with real-time weather APIs  
- Deployment using Streamlit or Flask  
- IoT-based soil sensor integration  
- Explainable AI using SHAP  

---

##  Conclusion
This project demonstrates the effective use of machine learning for agricultural decision support by combining data analysis, model optimization, and intelligent crop recommendation, contributing towards smarter and sustainable farming practices.
