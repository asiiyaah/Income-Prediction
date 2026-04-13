# 📊 Income Prediction Using Machine Learning

## 📌 Project Overview

This project aims to predict whether a person earns **more than 50K** or **≤ 50K** per year based on demographic and work-related attributes.

The model is trained using a **supervised binary classification** approach on the **Adult Income Dataset**, which contains census data such as age, education, occupation, hours worked, etc.

---

## 🎯 Objective

- To analyze a structured dataset
- To preprocess and encode categorical data
- To build a machine learning model for income prediction
- To evaluate model performance using standard metrics

---

## 🧠 Machine Learning Approach

| Detail | Info |
|---|---|
| **Problem Type** | Binary Classification |
| **Target Variable** | `income` |
| **Classes** | `<=50K` → `0` / `>50K` → `1` |
| **Algorithm** | Logistic Regression (baseline model) |

---

## 📊 Dataset Description

The dataset contains the following features:

- Age
- Workclass
- Education
- Occupation
- Marital Status
- Hours per Week
- Capital Gain / Loss
- **Income** *(Target Variable)*

---

## ⚙️ Technologies Used

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data-lightgrey)

- Python 3.11
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code
- Git & GitHub

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/income-prediction-ml.git
cd income-prediction-ml
```

### 2️⃣ Create a Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Notebook

Open:
Select kernel: **Python 3.11 (venv)**

---

## 🧪 Model Training Steps

1. Load dataset using Pandas
2. Handle missing values
3. Encode categorical variables
4. Split dataset into training and testing sets
5. Train Logistic Regression model
6. Evaluate using accuracy and classification report

---

## ✅ Results

The trained model predicts whether a person earns:

| Prediction | Label |
|---|---|
| ≤ 50K | `0` |
| > 50K | `1` |

Based on input features such as **education**, **occupation**, and **work hours per week**.

---
## 📄 License

This project is for educational purposes.
