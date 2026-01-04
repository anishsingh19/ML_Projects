# 🌸 Iris Flower Classification

## 📌 Project Overview
This project focuses on building a multi-class classification system to predict the species of Iris flowers based on their physical measurements. The goal is to explore the full machine learning workflow, from exploratory data analysis to model comparison.

---

## ❓ Problem Statement
Given four numerical features — sepal length, sepal width, petal length, and petal width — predict the species of an Iris flower. The problem is a classic multi-class classification task with three target classes.

---

## 📊 Dataset
- **Name:** Iris Flower Dataset  
- **Source:** Kaggle (UCI ML Repository)  
- **Samples:** 150  
- **Features:** 4 numerical  
- **Target Classes:** 3 (Iris-setosa, Iris-versicolor, Iris-virginica)

Dataset was downloaded using Kaggle API in Google Colab.

---

## 🔍 Exploratory Data Analysis (EDA)
Key insights from EDA:
- The dataset is clean with no missing values.
- Petal length and petal width show strong discriminative power.
- Iris-setosa is clearly separable from the other two species.
- Sepal width contributes comparatively less to classification.

Correlation analysis revealed a strong positive correlation (≈0.96) between petal length and petal width.

---

## 🧠 Models Implemented
The following models were trained and evaluated:
- **K-Nearest Neighbors (KNN)**
- **Logistic Regression**
- **Support Vector Machine (SVM with RBF kernel)**

---

## 📈 Model Performance

| Model | Accuracy |
|------|----------|
| KNN | 1.00 |
| Logistic Regression | 0.9667 |
| SVM (RBF) | 0.9667 |

KNN achieved the highest accuracy due to its ability to capture local, non-linear patterns in the data.

---

## 🏆 Final Model Selection
**K-Nearest Neighbors (KNN)** was selected as the best-performing model for this dataset, achieving perfect classification on the test set.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Google Colab

---

## 📌 Conclusion
This project demonstrates how classical machine learning algorithms can effectively solve structured classification problems. Through EDA, feature understanding, and systematic model comparison, KNN was found to be the most suitable model for the Iris dataset.

---

## ✍️ Author
**Anish Singh**

