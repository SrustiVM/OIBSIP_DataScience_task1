# OIBSIP_DataScience_task1
Iris dataset analysis
# 🌸 Iris Flower Classification using Logistic Regression

## 📌 Project Overview
This project performs classification of Iris flower species using the Logistic Regression algorithm.  
The Iris dataset is one of the most popular datasets in Machine Learning and contains measurements of flower features such as sepal length, sepal width, petal length, and petal width.

The goal of this project is to predict the species of an Iris flower based on its features.

---

## 🎯 Objective
- Perform Exploratory Data Analysis (EDA)
- Visualize relationships between features
- Train a Logistic Regression classification model
- Evaluate model performance
- Understand important features affecting classification

---

## 📂 Dataset
Dataset Used: **Iris Dataset** from Scikit-learn

Features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target Classes:
- Setosa
- Versicolor
- Virginica

---

## 🛠️ Libraries Used
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## ⚙️ Steps Performed

### 1. Import Libraries
Imported required Python libraries for data analysis, visualization, and machine learning.

### 2. Load Dataset
Loaded the Iris dataset using Scikit-learn and converted it into a Pandas DataFrame.

### 3. Exploratory Data Analysis (EDA)
- Checked dataset structure
- Viewed summary statistics
- Checked missing values

### 4. Data Visualization
- Pairplot visualization using Seaborn
- Correlation heatmap

### 5. Data Preparation
Separated features (X) and target variable (y).

### 6. Feature Scaling
Applied StandardScaler for normalization of features.

### 7. Train-Test Split
Split dataset into training and testing sets.

### 8. Model Training
Trained Logistic Regression model on training data.

### 9. Prediction
Predicted flower species using test data.

### 10. Model Evaluation
Evaluated performance using:
- Accuracy Score
- Confusion Matrix
- Classification Report

### 11. Feature Importance
Analyzed model coefficients to understand feature importance.

---

## 📊 Results
- Logistic Regression achieved very high accuracy on the Iris dataset.
- Petal length and petal width were the most important features.
- Setosa flowers were perfectly separable from other classes.
- Slight overlap was observed between Versicolor and Virginica.

---

## 🔍 Key Insights
- Logistic Regression performs exceptionally well for Iris classification.
- Feature scaling improves model performance.
- Visualization helps understand class separability.

---

## 🚀 Outcome
Successfully built a Machine Learning classification model capable of predicting Iris flower species with high accuracy.

---

## 📁 Project Structure

```text
OIBSIP_Iris_Classification/
│
├── Iris_Classification.ipynb
├── README.md
