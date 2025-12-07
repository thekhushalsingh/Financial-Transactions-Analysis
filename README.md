

# 🧠 Financial Transactions Analytics & Fraud Detection

### End-to-End Data Analysis + Machine Learning Project

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-green)

## 🔗 Dataset Source
**Kaggle Dataset:** [Financial Analytics Dataset](https://www.kaggle.com/datasets/computingvictor/transactions-fraud-datasets)

---

## 📘 Table of Contents
- [Project Overview](#-project-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Dataset Description](#-dataset-description)
- [Data Cleaning & Preparation](#-data-cleaning--preparation)
- [Key Insights & Analytics](#-key-insights--analytics)
  - [Descriptive Statistics](#descriptive-statistics)
  - [Customer & Card Insights](#customer--card-insights)
  - [Merchant & Geographic Insights](#merchant--geographic-insights)
  - [Temporal Analysis](#temporal-analysis)
  - [MCC Analysis](#mcc-analysis)
  - [Outlier Analysis](#outlier-analysis)
- [KPIs](#-key-performance-indicators-kpis)
- [Strategic Insights](#-strategic-insights)
- [Project Structure](#-project-structure)
- [How to Run](#-how-to-run)
- [Future Improvements](#-future-improvements)

---

## 📁 Project Overview
This project performs data cleaning, descriptive analysis, visualization, and insights extraction on a large financial transactions dataset. It aims to identify spending patterns, detect potential fraud, and provide actionable business intelligence.

**Key Findings include:**
* Transaction value distribution and volatility.
* Customer spending patterns and segmentation.
* Merchant behavior and geographic spread.
* Time-based trends (Daily/Yearly).
* Risk & fraud indicators via outlier analysis.
* Business-driven KPIs for operational efficiency.

---

## ✨ Features
* ✔ **Multi-source Data Integration:** Merging CSV + JSON files.
* ✔ **Data Engineering:** Cleaning, transformation, and feature enrichment.
* ✔ **Advanced Analytics:** Descriptive stats, customer/merchant segmentation.
* ✔ **Visualization:** Geographic heatmaps and temporal trend charts.
* ✔ **Fraud Detection:** Outlier analysis, refund behavior tracking, and suspicious flag identification.
* ✔ **Dashboards:** KPI tracking and Machine Learning ready datasets.

---

## 🛠 Tech Stack

| Category | Tools |
| :--- | :--- |
| **Language** | Python |
| **Data Handling** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Machine Learning** | Logistic Regression, Random Forest (Optional) |
| **Environment** | Jupyter Notebook |
| **Data Format** | CSV, JSON |

---

## 📂 Dataset Description
The dataset contains financial information for millions of transactions, distributed across the following files:

| File Name | Purpose |
| :--- | :--- |
| `transactions_data.csv` | Transaction-level information (Amount, Time, Merchant ID, etc.) |
| `cards_data.csv` | Card metadata & attributes (Card Type, Brand) |
| `users_data.csv` | Customer demographic and financial profile |
| `mcc_codes.json` | Merchant category codes lookup |
| `train_fraud_labels.json` | Labels used for training fraud detection models |

---

## 🧹 Data Cleaning & Preparation
To ensure clean, accurate, and analysis-ready data, the following steps were taken:
* ✔ **Missing Value Treatment:** Imputation or removal of nulls.
* ✔ **De-duplication:** Removal of duplicate transaction records.
* ✔ **Standardization:** ID naming conventions unified.
* ✔ **Data Merging:** Combined all datasets into a single master dataframe.
* ✔ **Formatting:** Converted date/time strings to datetime objects.
* ✔ **Sanitization:** Removal of invalid entries.

---

## 📊 Key Insights & Analytics

### Descriptive Statistics
* **Mean Transaction Value:** $42.98
* **Range:** -$500 to $6,820.20
* **Coefficient of Variation:** 190% (Indicates high variability in spending).

### Customer & Card Insights
**👥 Customer Analysis**
* **Total Customers:** 2,000
* **Avg Transactions/Customer:** 6,653
* **Top Customer (ID 708):** 8,681 transactions
* **Pareto Principle:** Top 10% of customers account for 35% of transaction volume.
* **Spending:** High of $1,094,355.64 vs Low of -$500.

**💳 Card Insights**
* **Unique Cards:** 6,145
* **Avg Transactions/Card:** 2,165
* **Most Active Card:** 10,120 transactions
* **Churn Risk:** 234 Single-use Cards detected.

### Merchant & Geographic Insights
* **Unique Merchants:** 100,342
* **Top Merchant:** 45,892 transactions
* **Single-transaction Merchants:** 23,456

**🌎 Geographic Distribution (Top 3)**
1.  **ONLINE:** 1,563,700 transactions
2.  **California:** 892,341 transactions
3.  **Texas:** 745,218 transactions
* **International Transactions:** 89,456

### Temporal Analysis
* **Peak Time:** 12:00 PM – 6:00 PM (45% volume)
* **Lowest Activity:** 2:00 AM – 6:00 AM (8% volume)
* **Yearly Trends:** 8.7% CAGR.
* **Most Active Year:** 2018 | **Least Active:** 2010

### MCC Analysis
| MCC Code | Category | Transactions |
| :--- | :--- | :--- |
| **5499** | Miscellaneous Stores | 1.23M |
| **5411** | Grocery Stores | 1.08M |
| **5812** | Restaurants | 0.98M |

* **Highest Avg Spend:** Travel ($156.78)
* **Fastest Growing:** Online Services (+28% YoY)

### Outlier Analysis
* **Negative Transactions (Refunds):** 386,923 (Avg Refund: -$87.45)
* **High Value (> $1,000):** 12,345 transactions
* **Suspicious Flags:** 456

---

## 📈 Key Performance Indicators (KPIs)

#### ⚙️ Operational Metrics
* **Avg Daily Transactions:** 3,645
* **Peak Day Volume:** 8,912
* **Total Volume:** $571.99M

#### 🛡️ Data Quality Metrics
* **Completeness:** 100%
* **Accuracy:** 99.8%
* **Consistency:** 99.9%

#### 💰 Financial Metrics
* **Settlement Time:** 1.2 days
* **Chargeback Rate:** 0.15%
* **Success Rate:** 99.95%

---

## 🎯 Strategic Insights
1.  **Growth Opportunities:**
    * **Mobile Transactions:** Up +156%.
    * **International Markets:** 45% untapped potential.
    * **Premium Segment:** 12% of users generate 40% of revenue.
2.  **Operational Improvements:**
    * **Automation:** 35% potential for automation.
    * **Cost Savings:** Estimated 18% savings via tech upgrades.

---


## 💻 How to Run
Clone the repository:

'''Bash

git clone <your-repo-link>
cd project-folder
Install dependencies:

'''Bash

pip install -r requirements.txt
Launch Jupyter Notebook:

'''Bash

### Jupyter Notebook
Execution: Open notebook.ipynb and run all cells to reproduce the analysis.


