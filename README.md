# Machine Learning and Deep Learning Models for Predicting Bank Deposit Subscription

## 📌 Overview

This project was developed as part of the **Introduction to Artificial Intelligence** course at the **University of Sharjah**.

The aim of the project is to predict whether a bank customer will subscribe to a term deposit based on demographic, financial, and marketing-related features.

Three classification models were developed and compared:

- Logistic Regression
- Decision Tree
- Artificial Neural Network (ANN)

## 🎯 Objectives

The main objectives of this project are to:

- Prepare and preprocess the dataset.
- Handle numerical and categorical features.
- Apply machine learning classification techniques.
- Develop a deep learning model using an Artificial Neural Network.
- Compare the performance of different models.
- Evaluate the models using Accuracy, Precision, Recall, and F1-Score.

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔄 Data Preprocessing

The dataset contains demographic, financial, and marketing-related features.

The preprocessing steps include:

- Checking for missing values
- Separating numerical and categorical features
- Standardizing numerical features using `StandardScaler`
- Encoding categorical features using `OneHotEncoder`
- Splitting the dataset into 80% training and 20% testing data

## 🤖 Machine Learning Models

### 1. Logistic Regression

Logistic Regression was used as a baseline classification model.

### 2. Decision Tree

A Decision Tree classifier was used to model nonlinear relationships between the input features and the target variable.

### 3. Artificial Neural Network

A deep learning Artificial Neural Network was developed using Keras. The network uses multiple dense layers with ReLU activation and dropout layers to reduce overfitting.

## 📊 Results

The models were evaluated using Accuracy, Precision, Recall, and F1-Score.

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 91.56% | 71.11% | 50.73% | 59.22% |
| Decision Tree | 90.49% | 60.39% | 61.74% | 61.05% |
| Artificial Neural Network | 93.13% | 73.80% | 66.91% | 70.19% |

The **Artificial Neural Network achieved the highest accuracy and F1-Score** among the three models.

## 👩‍💻 My Contribution

My contribution focused on:

- Introduction and project background
- Analysis of the problem and project objectives

## 📁 Files

- `bank_deposit_prediction.ipynb` — Jupyter Notebook containing the data preprocessing, model development, predictions, and evaluation.
- `project code as txt.txt` — Plain-text version of the project code.

## 🚀 Future Improvements

Possible improvements include:

- Testing additional machine learning algorithms.
- Applying techniques to address class imbalance.
- Performing hyperparameter tuning.
- Improving model interpretability.
- Comparing additional deep learning architectures.
