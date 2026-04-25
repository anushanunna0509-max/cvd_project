# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Overview
This project focuses on predicting the presence of **heart disease** using machine learning models.  
It uses the **UCI Heart Disease dataset (Cleveland subset)** and applies data preprocessing, visualization, and multiple classification algorithms to build an accurate prediction system.

The goal is to assist in early detection of heart disease using data-driven insights.

---

## 🚀 Features
- 📊 Data preprocessing and cleaning
- 🔍 Exploratory Data Analysis (EDA)
- 🧹 Handling missing values using imputation
- 🔄 Encoding categorical variables
- 📈 Data visualization using Seaborn & Matplotlib
- 🤖 Multiple ML models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- 📉 Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC-AUC Curve

---

## 🏗️ Tech Stack
- **Programming Language:** Python  
- **Libraries:**
  - Pandas, NumPy
  - Matplotlib, Seaborn
  - Scikit-learn  
- **Environment:** Jupyter Notebook  

---

## 📂 Project Structure
cvd_project/
│── cvd_final_.ipynb # Main notebook with full implementation
│── README.md # Project documentation


---

## 📊 Dataset
- Dataset: **UCI Heart Disease Dataset**
- Subset Used: **Cleveland dataset**
- Target Variable:
  - `0` → No Heart Disease  
  - `1` → Presence of Heart Disease  

---

## ⚙️ Workflow

### 1. Data Loading
- Load dataset using Pandas
- Filter Cleveland dataset

### 2. Data Preprocessing
- Handle missing values:
  - Mean (numerical)
  - Most frequent (categorical)
- Label Encoding for categorical features
- Convert target into binary classification

### 3. Exploratory Data Analysis
- Missing value heatmap
- Target distribution visualization
- Feature histograms

### 4. Model Building
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### 5. Model Evaluation
- Accuracy Score
- Precision, Recall, F1 Score
- ROC Curve & AUC Score

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/anushanunna0509-max/cvd_project.git
cd cvd_project
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
