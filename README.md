# 🚦 Queensland Traffic Crash Analysis and Predictive Modelling

Machine learning analysis of over **20 years of Queensland Government traffic crash data** to predict crash severity and identify high-risk crash locations using spatial analysis and classification models.

---

## 📌 Project Overview

This project analyses traffic crash records collected by the **Queensland Government** between **2001 and 2023**. By integrating road roughness data through spatial matching, the project explores the factors associated with crash severity and develops machine learning models for prediction and hotspot identification.

The project was completed as part of my **Master of Data Science** at **The University of Queensland**.

---

## 🎯 Objectives

- Predict traffic crash severity using machine learning.
- Identify high-risk crash hotspots using clustering algorithms.
- Analyse factors contributing to severe traffic accidents.
- Support data-driven road safety decision making.

---

## 🗂 Dataset

### Queensland Traffic Crash Data
- Source: Queensland Government Open Data
- Time period: 2001–2023
- Includes:
  - Crash severity
  - Driver information
  - Vehicle information
  - Road conditions
  - Speed limit
  - Alcohol involvement
  - Weather conditions

### Road Roughness Dataset
- Road surface condition measurements
- Integrated using KDTree spatial matching

---

## 🛠 Technologies

| Category | Technologies |
|----------|--------------|
| Programming | Python |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Algorithms | Random Forest, SVM, DBSCAN |
| Spatial Analysis | KDTree |
| Visualisation | Matplotlib, Seaborn |
| Notebook | Jupyter Notebook |

---

## 📊 Project Workflow

```text
Raw Data
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis (EDA)
      │
      ▼
Road Roughness Integration (KDTree)
      │
      ▼
Machine Learning
(Random Forest / SVM)
      │
      ▼
DBSCAN Hotspot Detection
      │
      ▼
Results & Visualisation
```

---

## 📈 Key Results

- Analysed over **20 years** of Queensland traffic crash records.
- Integrated road roughness information using **KDTree**.
- Performed comprehensive exploratory data analysis.
- Built crash severity prediction models using:
  - Random Forest
  - Support Vector Machine (SVM)
- Identified traffic accident hotspots using **DBSCAN** clustering.
- Generated visual insights to support road safety planning.

---

## 📂 Repository Structure

```text
qld-traffic-crash-analysis
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Preprocessing.ipynb
│   ├── 03_RandomForest.ipynb
│   ├── 04_SVM.ipynb
│   └── 05_DBSCAN.ipynb
│
├── report/
│   └── Thesis.pdf
│
├── images/
│
├── requirements.txt
│
└── README.md
```

---

## 🚀 Future Improvements

- Apply XGBoost and LightGBM for model comparison.
- Improve model interpretability using SHAP.
- Incorporate weather and traffic volume data.
- Deploy an interactive dashboard using Streamlit or Power BI.

---

## 👤 Author

**Yupeng Tang**

Master of Data Science  
The University of Queensland

LinkedIn:

https://www.linkedin.com/in/yu-peng-tang-3b1605221

---

## 📄 License

This project is licensed under the MIT License.
