# 📊 Telecom Customer Churn Prediction using Logistic Regression

## 📌 Project Overview

Customer churn means when customers stop using a company's service.
In the telecom industry, predicting churn helps companies keep customers and reduce revenue loss.
This project builds a **Logistic Regression model** to predict whether a customer will churn or not.

The model analyzes customer data such as contract type, monthly charges, and internet service to identify churn patterns.

---

# 📂 Dataset

The dataset used is the **Telecom Customer Churn Dataset**.

It contains customer information such as:

* Customer ID
* Gender
* Senior Citizen
* Tenure
* Internet Service
* Contract Type
* Monthly Charges
* Total Charges
* Churn (Target Variable)

Target Variable:

* **Churn = Yes (Customer leaves)**
* **Churn = No (Customer stays)**

---

# 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Statsmodels
* Jupyter Notebook

---

# ⚙️ Project Workflow

### 1️⃣ Data Collection

The telecom churn dataset was loaded and explored.

### 2️⃣ Data Cleaning

* Removed missing values
* Converted categorical variables to numeric
* Checked data types

### 3️⃣ Exploratory Data Analysis (EDA)

Data visualization was used to understand patterns in churn.

Examples:

* Churn vs Contract type
* Churn vs Tenure
* Churn vs Monthly Charges

### 4️⃣ Data Preprocessing

* Converted categorical variables using **Dummy Variables**
* Scaled numerical features if required
* Split dataset into **training and testing sets**

### 5️⃣ Model Building

A **Logistic Regression model** was trained to predict customer churn.

The model calculates the probability that a customer will churn.

### 6️⃣ Model Evaluation

The model was evaluated using:

* Confusion Matrix
* Accuracy
* Precision
* Recall (Sensitivity)
* Specificity
* ROC Curve
* AUC Score

---

# 📊 Model Performance

Evaluation metrics used:

* **Accuracy** – Measures overall correctness of the model
* **Precision** – Measures correct positive predictions
* **Recall (Sensitivity)** – Measures ability to detect churn customers
* **Specificity** – Measures ability to detect non-churn customers
* **ROC Curve** – Shows trade-off between True Positive Rate and False Positive Rate

---

# 📈 Key Insights

* Customers with **month-to-month contracts** have higher churn.
* **Higher monthly charges** increase churn probability.
* Customers with **longer tenure** are less likely to churn.
* **Fiber optic internet users** show higher churn rates.

---

# 📌 Conclusion

The Logistic Regression model successfully predicts customer churn using telecom customer data.

This model helps telecom companies:

* Identify customers likely to churn
* Take preventive actions
* Improve customer retention
* Reduce revenue loss
