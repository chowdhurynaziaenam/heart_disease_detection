# Prediction on Heart disease 
This project demonstrates the relationship between various health predictors for patients such as age, blood pressure, heart rate, exercise induced angina, presence or absence of heart disease and so on. The major goal was to build a predictive model to identify individuals with heart disease accurately. 


## Table of Contents

* [General overview](#general-overview)
* [Project Structure](#project-structure)
* [Environment](#environment)
* [Libraries & Packages](#libraries-&-packages)
* [ML models used](#ml-models-used)
* [Evaluation Metrics](#evaluation-metrics)
* [Results](#results)
* [Setup](#setup)
* [Acknowledgement](#acknowledgement)
  

## General Overview

This project focused on the analysis of  multivariate type of dataset for heart disease prediction. The project analyses the previous Cleveland dataset of 'UCI Heart disease dataset' obtained from UCI ML repository The dataset consists of 303 entries and 14 attributes which are age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise relative to rest, the slope of the peak exercise ST segment, number of major vessels, Thalassemia and target attribute indicating presence or absence of heart disease. No missing values were found in the dataset as each column has 303 non-null entries.


## Project Structure

The tasks of the project included-
1. Exploratory data analysis for features
2. Checking for missing values
3. Finding correlation between variables
4. Developing predictive model using 9 classifiers to detect individuals with heart disease
5. Assess performance of classifiers based on Accuracy, ROC score, Recall, F1-score and Precision

## Environment

The project was executed using Google Colab.

## Libraries & Packages 

* Seaborn: For data visualization
* NumPy: For numerical operations
* Matplotlib: For plotting graphs
* Pandas: For data manipulation and analysis
* Scikit-learn (sklearn): For machine learning model development and evaluation
  
## ML models used

The predictive performance of the following six classifiers was assessed:
* Random Forest
* Support Vector Machine (SVM)
* Decision Tree
* K-Nearest Neighbors (K-NN)
* Logistic Regression
* Gradient Boosting


## Evaluation Metrics

The models were evaluated using the following metrics:
* Accuracy
* Recall
* F1-score
* Precision

## Results




## Setup

* Open Google Colab
* Upload the notebook or open it directly from Google Drive
* Ensure all required packages are installed
* Run the cells sequentially to execute the analysis

## Acknowledgements

Originally dataset available at: https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data

Dataset available at Kaggle: https://www.kaggle.com/datasets/arezaei81/heartcsv

Creators of dataset:
Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.
