# Customer Churn Analysis 🚀

![Python](https://img.shields.io/badge/Python-3.11-blue) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange) ![License](https://img.shields.io/badge/License-MIT-green)

---

## 📊 Project Overview

This project analyzes customer churn to uncover key factors influencing attrition and provides actionable insights to improve retention. Using exploratory data analysis (EDA) and visualizations, high-risk customer segments are identified, guiding strategies to enhance customer lifetime value.

---

## 📈 Key Metrics

| Metric                | Value                           | Insight                                                                       |
| --------------------- | ------------------------------- | ----------------------------------------------------------------------------- |
| **Churn Rate**        | ~26–27%                         | Indicates significant retention challenge                                     |
| **High-Risk Segment** | 1–2 Months Tenure               | Most churn occurs early, highlighting onboarding issues                       |
| **Contract Impact**   | 85–90% churn for Month-to-Month | Longer contracts improve retention                                            |
| **Service Usage**     | Low adoption of add-ons         | Lack of OnlineSecurity, Backup, DeviceProtection, TechSupport increases churn |
| **Payment Method**    | Electronic Checks               | Manual payments increase churn; automated payments reduce risk                |

---

## 🎯 Objective

* Identify drivers of customer churn
* Highlight high-risk customer segments
* Recommend actionable strategies to reduce churn

---

## 🔍 Exploratory Data Analysis (EDA)

### 1️⃣ Data Cleaning & Preprocessing

* Handled missing values and converted categorical variables to analyzable formats

### 2️⃣ Tenure Analysis

* Churn concentrated among new customers (1–2 months)
  ![Churn by Tenure](reports/tenure_churn.png)

### 3️⃣ Contract Type Analysis

* Month-to-month subscribers churn most; longer contracts improve retention
  ![Churn by Contract Type](reports/contract_churn.png)

### 4️⃣ Service Usage Patterns

* Low adoption of add-on services correlates with higher churn
  ![Service Usage vs Churn](reports/service_usage_churn.png)

### 5️⃣ Payment Method Analysis

* Electronic check payments linked to higher churn; automated payments improve retention
  ![Payment Method Impact](reports/payment_churn.png)

---

## 💡 Recommendations

* Enhance onboarding for new customers to reduce early-stage churn
* Promote long-term contracts and bundled services
* Encourage automated payment adoption for better retention

---

## 🛠 Tools & Technologies

* **Python** – Data analysis
* **Pandas & NumPy** – Data cleaning & preprocessing
* **Matplotlib & Seaborn** – Visualizations
* **Jupyter Notebook** – Interactive workflow

---

## 📂 Project Structure

```
Customer_Churn_Analysis/
│
├── data/                   # Dataset files
├── notebooks/              # EDA & analysis notebooks
├── reports/                # Visualizations (png files)
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies
```

---

## ⚡ How to Run

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook in `notebooks/` to explore analysis and visualizations

---

## 🎯 Outcome

This project provides actionable insights to identify high-risk customers early, optimize retention strategies, improve customer lifetime value, and enhance overall business performance.
