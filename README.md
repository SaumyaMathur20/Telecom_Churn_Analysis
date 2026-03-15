# 📊 Telecom Customer Churn Analysis (Exploratory Data Analysis)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a telecom customer dataset to identify patterns and factors influencing **customer churn**.

The analysis focuses on understanding how **demographics, services, contract type, tenure, and payment methods** affect the probability of customers leaving the telecom service.

The entire workflow was implemented using **Python for data cleaning, transformation, and visualization**.

---

# 🛠️ Tools & Technologies

**Python**
* **Pandas** – Data cleaning & manipulation
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization

---

# 📂 Dataset Information

The dataset contains **telecom customer records** including:

* Customer demographics
* Service subscriptions
* Account information
* Payment methods
* Contract details
* Customer churn status

### Key Dataset Characteristics

* Multiple categorical and numerical variables
* Customer behavioral and subscription data
* Binary target variable: **Churn (Yes / No)**

---

# 🔧 Data Preprocessing

The following preprocessing steps were performed before analysis:

✔ Converted **TotalCharges** column from string to numeric format
✔ Handled blank values in TotalCharges by replacing them with **0**
✔ Checked dataset structure using `.info()` and `.describe()`
✔ Verified **duplicate customer IDs**
✔ Transformed the **SeniorCitizen** column from numeric (0/1) to categorical (Yes/No) for better interpretability

---

# 📊 Exploratory Data Analysis

The analysis uses multiple visualizations including:

* Count plots
* Pie charts
* Histograms
* Multi-variable comparison plots

These visualizations help identify **customer churn patterns across different attributes**.

---

# 📈 Key Insights

## 1️⃣ Overall Churn Distribution

* Approximately **26–27% of customers have churned**
* Around **73–74% customers remain active**

This indicates a **moderate churn rate**, which telecom companies typically try to reduce below **20%**.

---

## 2️⃣ Gender vs Churn

* Churn behavior between **male and female customers is almost identical**
* No significant gender-based difference in churn rate

➡️ **Gender is not a strong predictor of churn**

---

## 3️⃣ Senior Citizen Analysis

* Senior citizens represent roughly **16% of the customer base**
* Despite being a smaller segment, **senior citizens show relatively higher churn rates**

➡️ Older customers may require **better customer support and retention strategies**

---

## 4️⃣ Tenure vs Churn

The tenure distribution reveals a strong pattern:

* Customers with **short tenure (0–12 months)** have the **highest churn rate**
* Customers staying **longer than 24 months** show **significantly lower churn**

➡️ Early customer lifecycle is the **most critical period for retention**

---

## 5️⃣ Contract Type Impact

Contract type is one of the **strongest indicators of churn**.

| Contract Type  | Churn Trend    |
| -------------- | -------------- |
| Month-to-Month | Highest churn  |
| One-Year       | Moderate churn |
| Two-Year       | Lowest churn   |

➡️ Customers on **month-to-month contracts are significantly more likely to churn**

---

## 6️⃣ Payment Method Analysis

Churn rates vary across payment methods:

* **Electronic Check users show the highest churn**
* **Automatic payment methods (bank transfer / credit card)** show lower churn rates

➡️ Automatic payment options may improve **customer retention**

---

## 7️⃣ Service Feature Analysis

Multiple service features were analyzed including:

* Internet service
* Online security
* Online backup
* Device protection
* Tech support
* Streaming services

Key observations:

* Customers **without security or tech support services** show **higher churn**
* Value-added services appear to **improve customer retention**

---

# 📊 Visualizations Included

The project includes multiple charts such as:

* Customer churn distribution
* Gender vs churn comparison
* Senior citizen analysis
* Tenure distribution with churn overlay
* Contract type churn comparison
* Payment method churn comparison
* Multi-feature churn comparison grid

These visualizations help uncover **hidden patterns in customer behavior**.

---

# 📉 Business Insights

From a business perspective, the analysis suggests:

✔ Focus retention strategies on **new customers (low tenure)**
✔ Encourage **long-term contracts**
✔ Promote **automatic payment methods**
✔ Offer **value-added services** like tech support and security

These actions can help telecom companies **reduce churn and improve customer lifetime value**.

---

# 🚀 Project Outcomes

This project demonstrates practical skills in:

* Data cleaning
* Exploratory data analysis
* Data visualization
* Business insight extraction
* Customer churn analytics

---

# 📁 Repository Structure

```
Telecom-Churn-Analysis/
│
├── Telecom_Churn_EDA.ipynb
├── dataset/
│   └── Customer Churn.csv
└── README.md
```

---

# 👩‍💻 Author

**Saumya Mathur**

---
