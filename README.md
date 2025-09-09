# 🫀 Prediction on Heart disease 

![Python](https://img.shields.io/badge/Python-3.10-blue.svg?logo=python&logoColor=white)   ![Pandas](https://img.shields.io/badge/pandas-Data%20Analysis-blue?logo=pandas)  
![NumPy](https://img.shields.io/badge/numpy-Numerical-green?logo=numpy)  ![Matplotlib](https://img.shields.io/badge/matplotlib-Visualization-yellow)  ![Seaborn](https://img.shields.io/badge/seaborn-Stats%20Plots-lightblue)  ![Scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikitlearn)  ![Machine Learning](https://img.shields.io/badge/Models-9%20Classifiers-success)  

This project demonstrates the relationship between various health predictors for patients such as age, blood pressure, heart rate, exercise induced angina, presence or absence of heart disease and so on. The major goal was to build a predictive model to identify individuals with heart disease accurately. 

---

## 📜 Table of Contents

* [General overview](#general-overview)
* [Project Structure](#project-structure)
* [Environment](#environment)
* [Libraries & Packages](#libraries-&-packages)
* [ML models used](#ml-models-used)
* [Evaluation Metrics](#evaluation-metrics)
* [Results](#results)
* [Setup](#setup)
* [Acknowledgement](#acknowledgement)

---

## ✨ General Overview

This project focused on the analysis of  multivariate type of dataset for heart disease prediction. The project analyses the previous Cleveland dataset of 'UCI Heart disease dataset' obtained from UCI ML repository The dataset consists of 303 entries and 14 attributes which are age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise relative to rest, the slope of the peak exercise ST segment, number of major vessels, Thalassemia and target attribute indicating presence or absence of heart disease. No missing values were found in the dataset as each column has 303 non-null entries.

---

## 📂 Project Structure

The tasks of the project included-
1. Exploratory data analysis for features
2. Checking for missing values
3. Finding correlation between variables
4. Developing predictive model using 9 classifiers to detect individuals with heart disease
5. Assess performance of classifiers based on Accuracy, Recall, AUC, ROC Curve, F1-score and Precision

---

## 🖥️ Environment

The project was executed using Google Colab.

---


## 📚 Libraries & Packages

- 🐼 **pandas** → data manipulation  
- 🔢 **NumPy** → numerical operations  
- 📈 **Matplotlib** → plotting graphs  
- 📊 **Seaborn** → statistical visualization  
- 🤖 **Scikit-learn** → ML model development & evaluation

--- 
  
## 📈 ML models used

The predictive performance of the following 9 classifiers was assessed:
* Adaboost
* Random Forest
* Support Vector Machine 
* Decision Tree
* Nearest Neighbors
* Logistic Regression
* Gradient Boosting
* Naive Bayes
* Neural Net

---


## ✅ Evaluation Metrics

The models were evaluated using the following metrics:
* Accuracy
* Recall
* F1-score
* Precision
* Area Under the curve(AUC)
* ROC( Receiver operating characteristic) curve

---


## 📊 Results

- 💡Adaboost showed highest accuracy of 86.84% and 0.93 recall.
- Most classifiers performed above **80%** accuracy.  
- KNN had lowest accuracy & F1-score.  
- Random Forest & Naive Bayes → recall of **0.91**.  
- Neural Net & SVM → ~68% accuracy. 

---


## 🛠️ Setup

* Open Google Colab
* Upload the notebook or open it directly from Google Drive
* Ensure all required packages are installed
* Run the cells sequentially to execute the analysis

---

## 🙌 Acknowledgements

Originally dataset available at: https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data

Dataset available at Kaggle: https://www.kaggle.com/datasets/arezaei81/heartcsv

Creators of dataset:
* Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
* University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
* University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
* V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.




