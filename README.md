# 🏦 Internship Task 2 – Loan Prediction

## 🧠 Objective
The objective of this task was to build a machine learning model to predict whether a loan will be approved or not based on various customer features such as education, income, self-employment status, etc.

## 📊 Dataset
- **Source:** Provided dataset `loan_approval_dataset.csv`
- **Target Variable:** Loan Status (Approved / Rejected)
- **Features:** Education, Self Employed, Loan Amount, Income, etc.

## 🔧 Steps Performed

### 🔹 Data Preprocessing
- Checked for missing values
- Cleaned column names
- Used Label Encoding for categorical variables like `education`, `self_employed`, and `loan_status`

### 🔹 Exploratory Data Analysis (EDA)
- Histogram of loan amount
- Loan status comparison by education level
- Boxplot of income vs loan approval

### 🔹 Model Building
- Split dataset into train (80%) and test (20%) sets
- Trained:
  - **Logistic Regression**
  - **Decision Tree Classifier**

### 🔹 Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report

## 📈 Results
- Models were able to predict loan approval with reasonable accuracy
- **Education and income** had noticeable effects on loan status

## 📦 Libraries Used
- pandas, numpy
- seaborn, matplotlib
- scikit-learn

## 🗂️ Files
- `INTERNSHIP TASK 2.ipynb` – Notebook with code and analysis
- `README.md` – Project summary

## ✅ Status
Completed and uploaded as part of internship Task 2.
