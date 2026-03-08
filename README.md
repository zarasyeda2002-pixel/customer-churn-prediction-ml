# Customer Churn Prediction

Week 1 & Week 2: EDA + Machine Learning Models

---

## 📌 Course Information

**Course:** Introduction to Applied Artificial Intelligence  
**Semester:** BS 8th Semester  
**Project:** Customer Churn Prediction  
**Author:** Syeda Fatima Zahra  
**Date:** 08/03/2026  

---

## 📊 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** and building **predictive machine learning models** on the Telco Customer Churn dataset.

### Goals

- Understand customer behavior patterns  
- Identify factors contributing to customer churn  
- Build machine learning models to predict churn  
- Discover high-risk customer groups  
- Generate useful business insights  

---

## 📂 Dataset Information

**Source:** Telco Customer Churn Dataset (Kaggle)  

- **Total Customers:** 7,043  
- **Total Features:** 21  
- **Target Variable:** Churn (Yes / No)  

⚠️ **Note:** The dataset file (`customer_data.csv`) is not included in this repository.  
Please download it from Kaggle and place it in the project folder before running the notebooks.

---

## 📁 Repository Structure
week1-eda.ipynb → Exploratory Data Analysis notebook
week2-ml-models.ipynb → Machine Learning models for churn prediction
README.md → Project documentation

---

## 🔍 Key Insights

### Week 1: EDA

- Customers with **month-to-month contracts** have higher churn rates.  
- Customers with **short tenure (< 6 months)** are more likely to churn.  
- **Higher monthly charges** are associated with increased churn.  
- **Fiber optic internet users** show higher churn compared to DSL users.  
- Customers using **electronic check payment method** have higher churn rates.

---

### Week 2: Machine Learning Models

Trained and compared three machine learning models:

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

Models were evaluated using:

- Accuracy  
- Classification Report  
- Confusion Matrix  

---

## ⚙️ Feature Engineering

New features were created to improve model performance:

- **TotalRevenue = tenure × monthly charges**  
- **TotalServices = number of active services**  
- **TenureGroup = grouped tenure categories**  
- **HighCharges = flag for high monthly charges**

After feature engineering, the **Random Forest model** was retrained and showed improved performance.

---

## 📊 Typical Model Accuracy

| Model | Accuracy Range |
|------|------|
| Logistic Regression | 75–80% |
| Decision Tree | 72–78% |
| Random Forest | 78–83% |

---

## ⭐ Important Features

Some of the most influential features in predicting churn include:

- Contract type (month-to-month)  
- Tenure (customer duration)  
- Monthly Charges  
- Internet Service type  
- Payment Method  

---

## ⚙️ Setup Instructions

Install required libraries:
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

Run the notebooks:
jupyter notebook week1-eda.ipynb
jupyter notebook week2-ml-models.ipynb

---

## 🚀 Next Steps

- Hyperparameter tuning for better model performance  
- Experiment with additional feature combinations  
- Handle class imbalance in the dataset  
- Try advanced models for better predictions  

---

## 🎯 Learning Outcomes

Through this project, I learned:

- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Data visualization using **Matplotlib and Seaborn**  
- Building and comparing machine learning models  
- Evaluating model performance using metrics  
- Feature engineering techniques  
- Extracting business insights from data  
- Using **Git and GitHub for version control**

---

## 📬 Contact

**Author:** Syeda Fatima Zahra  

GitHub: zarasyeda
