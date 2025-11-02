# Bank-Loan-Case-study-analysis

This project analyzes financial and demographic loan applicant data to identify factors that contribute to loan default. The objective was to help banks improve credit risk assessment and reduce the chance of approving loans to high-risk applicants.

---

## 🎯 Goal of the Project
To identify key patterns and risk indicators that differentiate **defaulters** from **non-defaulters**, so the bank can make informed loan approval decisions.

---

## ✅ What I Did
- Cleaned and prepared a dataset containing **100+ customer attributes**
- Removed **40+ columns** with more than **40% missing values** to prevent incorrect analysis
- Handled numeric missing values using **median imputation**
- Detected and removed **extreme outliers** using the **IQR method**
- Identified **high class imbalance** between defaulters and non-defaulters
- Performed **univariate, segmented, and bivariate analysis**
- Calculated **correlations** between key income and credit variables
- Visualized distributions and patterns using charts and pivot tables

---

## 🛠️ Tools & Skills Used
- **Microsoft Excel** (Power Query, Pivot Tables, Conditional Formatting, Scatter Plots, Histograms)
- **Excel Functions:** `COUNTIF`, `IF`, `MEDIAN`, `QUARTILE`, `CORREL`
- Data Cleaning, Outlier Treatment, Trend Analysis, Insight Communication

---

## 📊 Key Findings (With Measurements)
- **Dataset Imbalance:**  
  → **92%** non-defaulters vs **8%** defaulters  
  This means default cases are **11x fewer**, requiring careful interpretation.

- **Income vs Default Trend:**  
  Defaulters generally had **lower annual income** compared to non-defaulters.  
  Lower income group shows **higher default probability**.

- **Loan-to-Income Ratio Issue:**  
  In defaulters, **loan amount was not aligned with income**.  
  Correlation between income and loan amount in:
  - Non-defaulters ≈ **0.38**
  - Defaulters ≈ **0.01**  
  → **Lower correlation indicates financial mismatch → major risk factor.**

- **Occupation & Education Impact:**  
  Applicants from **laborer / low-skilled occupations** and **lower education levels** showed **significantly higher default rates**.

- **Outlier Effect Observation:**  
  Removing outliers improved the clarity of credit-related patterns and reduced misleading averages.

---

## ⭐ Final Insights
- **Loan approval must consider income-to-loan ratio strictly** to prevent default.
- Applicants with **lower education and unstable occupations** are at **higher risk**.
- The bank should **avoid approving loans where income does not support repayment**.
- Strong potential to build a **predictive scoring model** with these insights.

---

## 💡 What This Project Demonstrates
- Structured **data cleaning and preprocessing**
- Ability to **analyze financial and behavioral patterns**
- Strong understanding of **credit risk evaluation**
- Professional presentation of insights with **data-backed storytelling**

---

## ⭐ Project Status
✅ Completed  
🚀 Ready for Portfolio, LinkedIn Case Study & Interviews

