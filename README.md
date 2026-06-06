# 📊 FUTURE_DS_02 — Customer Retention & Churn Analysis

<div align="center">

![Future Interns](https://img.shields.io/badge/Future%20Interns-Data%20Science%20%26%20Analytics-blue?style=for-the-badge)
![Task](https://img.shields.io/badge/Task-02-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.x-yellow?style=for-the-badge&logo=python)
![Plotly](https://img.shields.io/badge/Plotly-Interactive-blueviolet?style=for-the-badge)

</div>

---

## 🧾 Project Overview

This project is part of the **Future Interns – Data Science & Analytics Internship Program**.

The goal of Task 2 is to perform a comprehensive **Customer Retention & Churn Analysis** on a telecom subscription dataset — identifying *why* and *when* customers leave, and delivering actionable business recommendations.

---

## 🎯 Objectives

| # | Objective |
|---|-----------|
| 1 | Analyze churn patterns across customer segments |
| 2 | Identify key drivers that lead to customer churn |
| 3 | Perform cohort-based retention analysis |
| 4 | Calculate customer lifetime value trends |
| 5 | Build an interactive Plotly analytics dashboard |
| 6 | Deliver actionable business recommendations |

---

## 📂 Repository Structure

```
FUTURE_DS_02/
│
├── dataset/
│   └── telecom_churn_data.csv        # Dataset (1,500 customers, 18 features)
│
├── notebook/
│   └── Analysis.ipynb                # Full EDA + statistical analysis
│
├── dashboard/
│   ├── Dashboard.ipynb               # Interactive Plotly dashboard
│   └── dashboard_preview.png         # Dashboard screenshot
│
├── images/
│   └── *.png                         # All exported chart images
│
├── insights/
│   └── key_insights.md               # Business insights & recommendations
│
├── requirements.txt
└── README.md
```

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| Python 3.x | Core programming |
| Pandas | Data cleaning & transformation |
| NumPy | Numerical operations |
| Matplotlib & Seaborn | Static visualizations |
| Plotly | Interactive dashboard |
| Jupyter Notebook | Development environment |

---

## 📁 Dataset Information

**Dataset:** Telecom Customer Churn (Synthetic)  
**Size:** 1,500 customers | 18 features

| Column | Description |
|--------|-------------|
| `Tenure_Months` | How long customer has been subscribed |
| `Contract` | Month-to-Month / One Year / Two Year |
| `MonthlyCharges` | Monthly billing amount |
| `InternetService` | Fiber Optic / DSL / No Internet |
| `PaymentMethod` | How the customer pays |
| `Churn` | 1 = Churned, 0 = Active |
| `ChurnReason` | Reason for leaving (if churned) |
| `CohortMonth` | Month of joining (for cohort analysis) |

---

## 📈 Analysis Performed

- ✅ Data Cleaning & Type Conversion
- ✅ KPI Summary (Churn Rate, Revenue at Risk, Avg Tenure)
- ✅ Univariate Analysis (Distributions)
- ✅ Bivariate Analysis (Churn vs Contract, Payment, Internet, Tenure)
- ✅ Cohort Retention Analysis
- ✅ Churn Reasons Breakdown
- ✅ Correlation Heatmap
- ✅ Scatter Plot (Tenure vs Charges)
- ✅ Regional Churn Analysis
- ✅ Interactive Plotly Dashboard

---

## 💡 Key Insights

> 📌 **Month-to-Month customers churn ~45%** — 5x higher than Two Year contract customers.

> 📌 **First 6 months are critical** — ~50% churn in early tenure; drops to ~12% after 36 months.

> 📌 **Fiber Optic users are most dissatisfied** — ~40% churn despite being a premium service.

> 📌 **Electronic Check = low commitment** — ~40% churn vs ~22% for auto-pay users.

> 📌 **Multi-product customers are loyal** — Bundling reduces churn significantly.

---

## 🚀 Business Recommendations

| Priority | Action |
|----------|--------|
| 🔴 High | Offer discounts to convert Month-to-Month → Annual plans |
| 🔴 High | Launch 90-day onboarding program for new customers |
| 🟡 Medium | Audit and fix Fiber Optic service quality |
| 🟡 Medium | Incentivize auto-pay adoption (cashback/offers) |
| 🟢 Low | Cross-sell bundles to single-product customers |
| 🟢 Low | Loyalty rewards at 24-month milestone |

---

## ▶️ How to Run

```bash
# 1. Clone repository
git clone https://github.com/yourusername/FUTURE_DS_02.git
cd FUTURE_DS_02

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run Analysis
jupyter notebook notebook/Analysis.ipynb

# 4. Run Interactive Dashboard
jupyter notebook dashboard/Dashboard.ipynb
```

---

## 📦 Requirements

```
pandas | numpy | matplotlib | seaborn | plotly | jupyter
```

---

## 👩‍💻 Author

**[Your Name Here]**  
Data Science & Analytics Intern — Future Interns  
🔗 [LinkedIn](#) | 🐙 [GitHub](#)

---

## ⭐ Acknowledgement

Completed as part of the **Future Interns Data Science & Analytics Internship — Task 2**.  
🌐 [futureinterns.com](https://futureinterns.com)

---
<div align="center"><i>⭐ Star this repo if you found it helpful!</i></div>
