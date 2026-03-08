# Customer Churn Prediction

This project focuses on analyzing and predicting customer churn using the Telco Customer Churn dataset. The project is divided into two main parts: Exploratory Data Analysis (EDA) and Machine Learning Model Development.

---

## Dataset
- **Source:** Telco Customer Churn Dataset (Kaggle)  
- **Records:** 7043 customers  
- **Features:** 21 columns  
- **Target Variable:** Churn (Yes/No)

---

## Week 1 – Exploratory Data Analysis (EDA)

File: `week1_eda.ipynb`

In Week 1, exploratory data analysis was performed to understand the dataset and identify patterns related to customer churn.

### Tasks Performed
- Loaded dataset using Pandas
- Checked dataset structure and data types
- Analyzed missing values
- Generated statistical summaries
- Created visualizations using Matplotlib and Seaborn
- Analyzed numerical and categorical features
- Performed correlation analysis

### Key Insights
- Customers with **month-to-month contracts** have higher churn rates.
- Customers with **shorter tenure** are more likely to churn.
- **Higher monthly charges** are associated with higher churn.
- Certain **payment methods** show higher churn percentages.

---

## Week 2 – Machine Learning Models

File: `week2_ml_models.ipynb`

In Week 2, machine learning models were built to predict customer churn.

### Data Preprocessing
- Handled missing values
- Converted `TotalCharges` to numeric format
- Encoded categorical variables using one-hot encoding
- Converted churn into binary values (Yes = 1, No = 0)
- Split dataset into training and testing sets

### Models Implemented
- Logistic Regression
- Decision Tree
- Random Forest

### Model Evaluation
Models were evaluated using:
- Accuracy
- Confusion Matrix
- Precision, Recall, and F1-score

### Model Comparison
The models were compared based on accuracy to determine the best-performing model.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Git & GitHub

---

## Project Files
