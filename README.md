📊 Income Prediction Using Machine Learning
📌 Project Overview

This project aims to predict whether a person earns more than 50K or less than or equal to 50K per year based on demographic and work-related attributes.

The model is trained using a supervised binary classification approach on the Adult Income Dataset, which contains census data such as age, education, occupation, hours worked, etc.

🎯 Objective

To analyze a structured dataset

To preprocess and encode categorical data

To build a machine learning model for income prediction

To evaluate model performance using standard metrics

🧠 Machine Learning Approach

Problem Type: Binary Classification

Target Variable: income

<=50K → 0

>50K → 1

Algorithm Used:

Logistic Regression (baseline model)

📊 Dataset Description

The dataset contains the following types of features:

Age

Workclass

Education

Occupation

Marital status

Hours per week

Capital gain/loss

Income (Target variable)

⚙️ Technologies Used

Python 3.11

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

VS Code

Git & GitHub

🚀 How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/your-username/income-prediction-ml.git
cd income-prediction-ml

2️⃣ Create virtual environment
python -m venv venv
venv\Scripts\activate

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run the notebook

Open:

notebooks/income_prediction.ipynb


Select kernel:

Python 3.11 (venv)

🧪 Model Training Steps

Load dataset using Pandas

Handle missing values

Encode categorical variables

Split dataset into training and testing sets

Train Logistic Regression model

Evaluate using accuracy and classification report

✅ Result

The trained model can predict whether a person earns:

≤ 50K

> 50K

Based on input features such as education, occupation, and work hours.
