# 🌸 Machine Learning on the Iris Dataset – 10 Model Comparison Project

This project applies **10 different machine learning models** on the classic **Iris dataset** to classify iris flowers based on their sepal and petal measurements.  
The goal is to analyze and compare the performance of various models and understand how they work under the hood.

---

## 📌 Objective

- Predict the species of an Iris flower using its **sepal** and **petal** features.
- Implement and evaluate **10 different ML models**.
- Save models, predictions, visualizations, and performance metrics.
- Visualize all model accuracies in a comparison chart.
- Build a strong foundation for future deployment (API + React UI).

---

## 📊 Dataset

**Source**: [Scikit-learn Iris Dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)  
**Size**: 150 samples, 4 features, 3 classes (`setosa`, `versicolor`, `virginica`)

**Features:**
- `sepal length (cm)`
- `sepal width (cm)`
- `petal length (cm)`
- `petal width (cm)`

**Target:**  
- `species` (3 classes)

---

## ⚙️ Technologies Used

- **Python 3.12**
- **Jupyter Notebook**
- **Scikit-learn**
- **Matplotlib / Seaborn**
- **XGBoost**
- **Pandas / NumPy**
- **Joblib** (for saving models)

---

## 🧠 Machine Learning Models Implemented

| Model # | Algorithm Name               |
|---------|------------------------------|
| 1       | Logistic Regression          |
| 2       | K-Nearest Neighbors (KNN)    |
| 3       | Naive Bayes                  |
| 4       | Support Vector Machine (SVM) |
| 5       | Decision Tree                |
| 6       | Random Forest                |
| 7       | Gradient Boosting            |
| 8       | XGBoost                      |
| 9       | AdaBoost                     |
| 10      | Extra Trees Classifier       |

Each model includes:
- Training on 80% of the dataset
- Prediction and accuracy evaluation on 20%
- Accuracy saved to `outputs/Accuracy/`
- Model saved to `models/` folder
- Visualizations (e.g., confusion matrix, PCA, decision boundary) saved to `outputs/`

---
