# Nutrition & Fruit Detection using Machine Learning and Deep Learning

This project focuses on **fruit classification and nutrition prediction** using various **machine learning and deep learning algorithms**.  
The system analyzes fruit images, predicts the fruit type, and provides corresponding **nutritional information** based on the trained model.

---

##  Project Overview

The goal of this project is to build an **intelligent fruit detection system** that:
- Classifies fruit images accurately.
- Predicts nutritional values.
- Compares performance across multiple ML/DL algorithms.
- Provides a user-friendly web interface for interaction.

The project integrates **Python-based model training** and a **Flask web application** for deployment.

---

##  Project Structure

├── BACKEND/
│ ├── CSS-JS/ # Static styling and JS scripts for web interface
│ ├── HTML/ # Frontend HTML templates (Flask integrated)
│ ├── app.py # Main Flask backend for web app
│ ├── nutrition.h5 # Trained nutrition prediction model
│
├── DATASET/
│ ├── ONE_HOT/ # Encoded dataset using one-hot encoding
│ ├── TEST_SET/ # Testing images
│ ├── TRAIN_SET/ # Training images
│
├── PYTHON_CODE/
│ ├── Baysian.py # Bayesian classifier
│ ├── CNN.py # Convolutional Neural Network model
│ ├── Decision-Tree.py # Decision Tree model
│ ├── Fruit_detection.ipynb # Main Jupyter notebook with analysis
│ ├── GRU.py # GRU-based RNN model
│ ├── KNN.py # K-Nearest Neighbors model
│ ├── LSTM.py # LSTM-based deep learning model
│ ├── SVM.py # Support Vector Machine model
│ ├── alexnet.py # AlexNet deep learning model
│ ├── c-means with KNN.py # Hybrid clustering with classification
│ ├── fuzzy.py # Fuzzy logic model implementation
│ ├── img-csv.py # Converts image dataset into CSV features
│ ├── linear.py # Linear Regression for numeric prediction
│ ├── logistic.py # Logistic Regression for classification
│ ├── naivebayes.py # Naive Bayes classifier
│ ├── one_hot_encoding.py # Feature encoding for categorical data
│ ├── ridge-lasso.py # Regularized regression models (Ridge/Lasso)
│ ├── sfa.py # Slow Feature Analysis model
│ ├── smote.py # Handles class imbalance using SMOTE
│
├── REPORT/
│ ├── Project_Report.docx # Project report and documentation
│
└── README.md 

