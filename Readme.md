# Telecom Customer Churn Analysis & Power BI Dashboard

## 📊 Project Overview

This project is a **Telecom Customer Churn Analysis** performed using Python and Microsoft Power BI.

The objective of the project is to understand customer churn, identify the factors associated with customer attrition, and build an interactive Power BI dashboard for business analysis.

The project follows a complete data analytics workflow:

**Raw Dataset → Data Inspection → Data Preparation → Exploratory Data Analysis → Visualization → Power BI Dashboard → Business Insights**

---

## 🎯 Project Objectives

The main objectives of this project are:

* Understand the structure of the telecom customer dataset
* Inspect data types and missing values
* Identify important customer churn patterns
* Analyze churn across different contract types
* Analyze churn across internet service types
* Analyze churn across payment methods
* Compare monthly charges between churned and retained customers
* Calculate important churn KPIs
* Build a professional Power BI dashboard
* Generate actionable business recommendations

---

## 🛠️ Tools & Technologies

### Python

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Google Colab

### Power BI

* Microsoft Power BI Desktop
* DAX
* Data Visualization
* KPI Cards
* Bar Charts
* Column Charts
* Line Charts
* Donut Chart

---

## 📁 Dataset

The project uses the **Telco Customer Churn dataset**.

Dataset source:

**Kaggle — Telco Customer Churn**

Dataset identifier:

`blastchar/telco-customer-churn`

The dataset contains customer information including:

* Customer demographics
* Tenure
* Phone services
* Internet services
* Online services
* Contract information
* Payment methods
* Monthly charges
* Total charges
* Customer churn status

---

## 📂 Project Structure

```text
telecom-customer-churn-analysis/
│
├── README.md
│
├── data/
│   └── telco_churn_cleaned.csv
│
├── python/
│   └── telecom_churn_analysis.ipynb
│
├── powerbi/
│   └── Telecom_Customer_Churn_Dashboard.pbix

```

---

## 🔍 Data Analysis

The dataset was first inspected using Python.

The analysis included:

* Dataset shape
* Column names
* Data types
* Missing-value analysis
* Unique-value analysis
* Churn distribution
* Customer segmentation
* Contract analysis
* Internet service analysis
* Payment method analysis
* Monthly charge analysis

---

## 📊 Churn Overview

The dataset contains:

| Churn Status | Customers |
| ------------ | --------: |
| No           |     5,174 |
| Yes          |     1,869 |
| **Total**    | **7,043** |

The overall customer churn rate is approximately:

**26.54%**

---

## 📈 Key Analysis Performed

### 1. Churn by Contract Type

The analysis shows a strong relationship between contract type and churn.

| Contract       | Churn Rate |
| -------------- | ---------: |
| Month-to-month |     42.71% |
| One year       |     11.27% |
| Two year       |      2.83% |

Month-to-month customers have significantly higher churn compared with customers on longer-term contracts.

---

### 2. Churn by Internet Service

| Internet Service    | Churn Rate |
| ------------------- | ---------: |
| DSL                 |     18.96% |
| Fiber optic         |     41.89% |
| No internet service |      7.40% |

Fiber-optic customers show substantially higher churn than DSL customers in this dataset.

---

### 3. Churn by Payment Method

| Payment Method            | Churn Rate |
| ------------------------- | ---------: |
| Electronic check          |     45.29% |
| Mailed check              |     19.11% |
| Bank transfer (automatic) |     16.71% |
| Credit card (automatic)   |     15.24% |

Electronic-check customers have the highest churn rate among the payment methods analyzed.

---

### 4. Monthly Charges

Average monthly charges were compared between customers who churned and those who remained.

| Churn Status | Average Monthly Charges |
| ------------ | ----------------------: |
| No           |                   61.27 |
| Yes          |                   74.44 |

Customers who churned had higher average monthly charges than customers who stayed.

---

## 📊 Power BI Dashboard

The Power BI dashboard was created to provide an interactive overview of customer churn.

### Main KPIs

* **Total Customers:** 7,043
* **Churned Customers:** 1,869
* **Churn Rate:** 26.54%

### Dashboard Visualizations

The dashboard includes analysis of:

* Churn rate by contract
* Churn rate by internet service
* Churn rate by payment method
* Churn by tenure
* Average monthly charges by churn
* Overall churn distribution
* Customer count by contract

---

## 🧮 DAX Measures

Several DAX measures were created for the Power BI dashboard.

### Total Customers

```DAX
Total Customers =
DISTINCTCOUNT('telco_churn_cleaned'[customerID])
```

### Churned Customers

```DAX
Churned Customers =
SUM('telco_churn_cleaned'[ChurnFlag])
```

### Churn Rate

```DAX
Churn Rate =
DIVIDE(
    [Churned Customers],
    [Total Customers]
)
```

These measures allow the dashboard visuals to dynamically calculate customer counts and churn rates.

---

## 💡 Business Value

The analysis can help a telecom business:

* Identify customers at higher risk of churn
* Understand the relationship between contracts and retention
* Investigate payment-method-related churn
* Analyze pricing-related churn patterns
* Improve customer retention strategies
* Identify customer groups requiring additional attention
* Support data-driven decision-making

---

## 📌 Project Outcome

This project demonstrates a complete beginner-to-intermediate **Data Analytics workflow** using Python and Power BI.

It demonstrates practical skills in:

* Data inspection
* Data preparation
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Exploratory Data Analysis
* Data visualization
* Power BI
* DAX
* Dashboard development
* Business analysis
* Business insights

---

## 👤 Author

**Aditya Kumar**

Aspiring Data Analyst

### Skills Demonstrated

`Python` `NumPy` `Pandas` `Matplotlib` `Seaborn`
`Power BI` `DAX` `Data Analysis` `Data Visualization`
`Dashboarding` `Business Intelligence` `Business Analysis`
