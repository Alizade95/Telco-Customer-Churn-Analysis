# 📉 Telco Customer Churn & Retention Analysis

## 📌 Project Overview
This project focuses on analyzing customer churn for a Telecommunications company to identify the key drivers behind customer attrition and provide actionable business recommendations to improve customer retention.

Using **Python (Pandas, Seaborn, Matplotlib)**, an Exploratory Data Analysis (EDA) was conducted on **7,043 customer records** to evaluate demographic factors, service subscriptions, contract types, and payment habits.

---

## 📊 Key Findings & Business Insights

* **Overall Churn Rate:** **26.54%** of total customers have left the service.
* **Contract Risk:** Customers on **Month-to-Month contracts** exhibit a churn rate over **40%**, whereas 1-2 year contract holders have churn rates below **10%**.
* **High-Risk Services:** **Fiber Optic** internet users show a high churn rate (**~42%**), indicating potential pricing or quality dissatisfaction compared to DSL users (**~19%**).
* **Impact of Tech Support:** Customers without **TechSupport** packages churn significantly more (**~41%**) than those who subscribe to support services (**~15%**).
* **Critical Period:** High customer drop-offs occur during the **first 12 months** of onboarding (tenure < 1 year).
* **Payment Method Friction:** **Electronic Check** users have the highest churn rate (**~45%**) compared to automated payment methods like Credit Card or Bank Transfer.

---

## 💡 Strategic Business Recommendations

1. **Incentivize Long-term Contracts:** Offer promotional discounts or loyalty points for customers switching from Month-to-Month to 1-year contracts.
2. **Bundle Support Services:** Provide complimentary TechSupport for the first 6 months to new Fiber Optic subscribers to improve initial retention.
3. **Optimize Onboarding (First 90 Days):** Launch targeted check-in campaigns for new customers in their first year to address early friction points.
4. **Promote Automated Payments:** Encourage auto-pay adoption with cashback or zero-fee incentives to reduce manual payment friction.

---

## 🛠️ Tech Stack & Methods
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Data Processing:** Data Cleaning, Type Conversion, Handling Missing Values
* **Exploratory Data Analysis (EDA):** Feature Categorization, Comparative Visualization, Distribution Analysis

---

## 📁 Repository Structure
```text
├── WA_Fn-UseC_-Telco-Customer-Churn.csv   # Raw Dataset
├── churn_analysis.ipynb                    # Jupyter Notebook with code & visualizations
└── README.md                              # Executive Summary & Project Documentation
