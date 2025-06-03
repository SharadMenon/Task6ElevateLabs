# 🌸 Iris Flower Classification using KNN, Logistic Regression & SVM

This project performs classification on the popular Iris dataset using **K-Nearest Neighbors (KNN)**, **Logistic Regression**, and **Support Vector Machine (SVM)** classifiers. The focus is on experimenting with KNN by varying the number of neighbors, evaluating model performance, and visualizing decision boundaries.

---

## 📁 Dataset
- **Source:** `sklearn.datasets.load_iris()`
- **Classes:** Setosa, Versicolor, Virginica
- **Features:**
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width

---

## ✅ Tasks Completed

### 1. Data Preprocessing
- Loaded Iris dataset
- Split data into training and test sets (80/20)
- Normalized features using `StandardScaler`

### 2. Classification Models
- Logistic Regression
- K-Nearest Neighbors (KNN) with varying `K`
- Support Vector Machine (Linear Kernel)

### 3. Model Evaluation
- **Accuracy Score** for all models
- **Confusion Matrix** for KNN models with `K = 1 to 10`
- **Accuracy vs K Plot** to choose optimal K

### 4. Visualization
- **Decision Boundaries** plotted after reducing data to 2D using PCA
- Visualized using both `matplotlib` and `seaborn`

---

## 📊 Key Visuals
- Confusion Matrices for K = 1 to 10
- Accuracy vs K Graph
- Decision boundaries for each classifier on PCA-reduced data

---

## 📦 Libraries Used
- `numpy`, `pandas`
- `matplotlib`, `seaborn`
- `sklearn` (for models, metrics, preprocessing, PCA)

---
