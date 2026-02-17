# ❤️ Heart Disease Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs an Exploratory Data Analysis (EDA) on a heart disease dataset to understand the distribution of patient attributes and their association with heart disease. The goal of this analysis is to uncover patterns, relationships, and insights from the data before applying any machine learning models.

EDA is a critical first step in any data science workflow, especially in medical datasets where interpretability and correctness are essential.

---

## 📊 Dataset Information
- **Source:** Kaggle (Heart Disease Dataset)
- **Type:** Medical / Clinical Data
- **Format:** CSV
- **Target Variable:** `target`  
  - `1` → Presence of heart disease  
  - `0` → No heart disease  

The dataset contains demographic, clinical, and diagnostic features related to heart health.

---

## 🧾 Feature Description

| Feature | Description |
|--------|-------------|
| age | Age of the patient (years) |
| sex | Sex (1 = male, 0 = female) |
| cp | Chest pain type |
| trestbps | Resting blood pressure (mm Hg) |
| chol | Serum cholesterol (mg/dl) |
| fbs | Fasting blood sugar (>120 mg/dl) |
| restecg | Resting electrocardiographic results |
| thalach | Maximum heart rate achieved |
| exang | Exercise-induced angina |
| oldpeak | ST depression induced by exercise |
| slope | Slope of the peak exercise ST segment |
| ca | Number of major vessels (0–3) |
| thal | Thalassemia |
| target | Heart disease presence |

---

## 🔍 Analysis Performed
The following EDA steps were carried out:

- Dataset loading and structure inspection
- Missing value analysis
- Univariate analysis of key features
- Feature vs target analysis
- Correlation analysis using heatmaps
- Interpretation of medical feature associations

---

## 📈 Key Insights
- Chest pain type (`cp`) and maximum heart rate achieved (`thalach`) show strong association with heart disease.
- Exercise-induced angina (`exang`) and ST depression (`oldpeak`) are negatively correlated with the target variable.
- Clinical features are more informative than demographic features such as age and sex in this dataset.
- Correlation analysis highlights important relationships useful for future model building.

---

## 🧠 Conclusion
This exploratory analysis highlights how EDA helps in understanding medical datasets by revealing key patterns and associations. The insights gained from this analysis provide a strong foundation for feature selection and predictive modeling in future work.

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 🚀 Future Work
- Build a heart disease prediction model
- Perform feature selection and scaling
- Compare correlation-based insights with model feature importance

---

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](LINK)

---

## 👤 Author
Anish Singh

