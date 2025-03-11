# 🌟 Liver Disease Prediction 🚀

## 📌 **Project Overview**
Welcome to the **Liver Disease Prediction** project! This machine learning model helps predict the presence of liver disease based on various health indicators.

## 📂 **Dataset Information**

📄 **File:** Indian_Liver_Patient_Dataset.csv

## 📊 **Features:**

- 🧑‍⚕️ **Age:** Age of the patient
  
- 🩸 **Total Bilirubin:** Level of bilirubin in blood
  
- 🩸 **Direct Bilirubin:** Direct bilirubin concentration
  
- 🧪 **Alkaline Phosphatase (ALP):** ALP enzyme level
  
- 🩸 **Alanine Aminotransferase (ALT):** ALT enzyme level
  
- 🩸 **Aspartate Aminotransferase (AST):** AST enzyme level
  
- 🧪 **Total Proteins:** Total protein level in blood
  
- 🧀 **Albumin:** Albumin concentration in blood
  
- 🧀 **Albumin and Globulin Ratio (A/G Ratio):** Ratio of albumin to globulin
  
- 🚻 **Gender:** Male or Female
  
- ⚕️ **Liver Disease Presence:** Target variable (1 - Disease, 0 - No Disease)

## 🔍 **Model Implementation**

📜 **File:** LIVER_DISEASE_PREDICTION.ipynb

🛠️ **Steps Followed:**

- 🏗️ **Data Preprocessing** - Handling missing values, encoding categorical data
  
- 📊 **Exploratory Data Analysis (EDA)** - Visualizing distributions and correlations

- 🤖 **Model Selection** - Training classification models
  
- 📈 **Model Evaluation** - Assessing accuracy and performance metrics

## 🤖 **Models Used**

- 🔹 Logistic Regression
  
- 🔹 Decision Tree Classifier
  
- 🔹 Random Forest Classifier
  
- 🔹 Support Vector Classifier (SVC)
  
- 🔹 XGBoost Classifier
  
- 🔹 K-Nearest Neighbors (KNN) Classifier
  
- 🔹 MLP Classifier

## 📉 **Metrics Used**

- 📌 Precision
  
- 📌 Recall
  
- 📌 F1-Score
  


## 🔍 **Hyperparameter Tuning & Optimization**

- ✅ Used  RandomizedSearchCV for optimal parameter selection.
  
- ✅ Applied cross-validation techniques for better model generalization.

## 🔑 **Key Insights**

- 🩸 High levels of bilirubin, AST, and ALT enzymes are strong indicators of liver disease.
  
- ⚖️ Albumin and Total Proteins also play a role in diagnosis.
  
- 🚻 Gender differences observed, with a slightly higher prevalence in males.

## 🎯 **Conclusion**

This project successfully predicts liver disease using multiple classification models. The K-Nearest Neighbors (KNN) provided the best performance. The findings highlight that **bilirubin levels, liver enzymes, and albumin concentration** are key factors in diagnosing liver disease.

