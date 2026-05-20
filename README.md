# Iris Flower Classification using Machine Learning

## 📌 Project Overview
This project is a Machine Learning classification system built using the famous Iris Flower Dataset. The model predicts the species of an Iris flower based on its physical measurements such as petal length, petal width, sepal length, and sepal width.

The project demonstrates the complete Machine Learning workflow including:
- Data loading
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Feature scaling
- Model training
- Performance evaluation
- Visualization of results

---

## 📂 Dataset
Dataset Used: **Iris Dataset**

The dataset contains measurements of three Iris flower species:
- Iris Setosa
- Iris Versicolor
- Iris Virginica

### Features
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target
- Species of Iris Flower

Dataset Source:
- Local File: `Iris.csv`
- Fallback URL:
https://raw.githubusercontent.com/amscotti/iris/master/iris.csv

---

## 🚀 Technologies & Libraries Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## What This Project Does

This project:
1. Loads the Iris dataset
2. Cleans and preprocesses the data
3. Performs Exploratory Data Analysis (EDA)
4. Visualizes feature correlations
5. Splits the dataset into training and testing sets
6. Applies feature scaling using `StandardScaler`
7. Trains a Logistic Regression classification model
8. Predicts flower species on test data
9. Evaluates model performance using:
   - Accuracy Score
   - Classification Report
   - Confusion Matrix
10. Saves visualizations as image files

---

## 🎯 Why This Project is Useful

This project is useful because it helps beginners understand:
- Basics of Machine Learning classification
- How supervised learning works
- Data preprocessing techniques
- Importance of feature scaling
- Model evaluation methods
- Visualization of ML results

It is also a great beginner-friendly project for:
- Academic mini projects
- Resume projects
- Learning Scikit-learn
- Understanding Logistic Regression

---

## 📊 Machine Learning Model Used

### Logistic Regression
The project uses the **Logistic Regression** algorithm with:
- Multinomial classification
- `lbfgs` solver
- Feature scaling for better performance

---

## 📈 Output Visualizations

The project generates:
- Feature Correlation Heatmap
- Confusion Matrix Heatmap

Saved Files:
- `iris_correlation_matrix.png`
- `iris_confusion_matrix.png`

---

## 🧪 Model Evaluation Metrics

The model performance is evaluated using:
- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

```text
Iris-Flower-Classification/
│
├── Iris.csv
├── iris_classification.py
├── iris_correlation_matrix.png
└── iris_confusion_matrix.png
 
