# CodTech-Task-1---Pipeline

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: RAHUL VERMA

*INTERN ID*: CTIS2711

*DOMAIN NAME*: DATA SCIENCE

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH

---

# 🎓 Student Performance Data Preprocessing Pipeline

This project demonstrates how to build a **complete automated data preprocessing pipeline** using **Python** and **Scikit-learn**. The goal is to transform raw student performance data into a **clean, machine-learning-ready format** using an industry-standard workflow.

---

## 📌 Project Objective

Raw datasets often contain:
- Missing values  
- Categorical text data  
- Features on different scales  

Machine learning models cannot work directly on such data.  
This project builds a **reusable preprocessing pipeline** that automatically handles all these issues.

---

## 🧠 What This Pipeline Does

The pipeline performs the following steps:

### 🔹 1. Handling Missing Values
- Numerical columns → Filled using **median**
- Categorical columns → Filled using **most frequent value**

### 🔹 2. Categorical Encoding
- Binary categories (Yes/No, Male/Female, etc.) are converted automatically  
- Multi-category columns (job, guardian, reason, etc.) are transformed using **One-Hot Encoding**

### 🔹 3. Feature Scaling
- Numerical features are standardized using **StandardScaler**
- This ensures all numeric features are on a similar scale

### 🔹 4. Full Automation using Pipeline
All preprocessing steps are combined into a **single Scikit-learn Pipeline**, ensuring:
- Consistent transformations
- Reusability on new/unseen data
- Production-ready workflow

---

## 🏗️ Technologies Used

- Python 🐍  
- Pandas  
- NumPy  
- Scikit-learn  

---

## 📂 Dataset

**Student Performance Dataset**

The dataset includes:
- Demographic details (age, address, family size, etc.)
- Academic history (study time, failures, grades)
- Social and lifestyle attributes

**Target Variable:**  
`G3` — Final grade of the student

---

# OUTPUT

<img width="761" height="320" alt="Image" src="https://github.com/user-attachments/assets/00d037a3-51e4-45aa-a62e-99606824b973" />
