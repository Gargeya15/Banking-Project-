# 🏦 Banking Customer Analytics & Segmentation Dashboard

🚀 An end-to-end Data Analytics + Machine Learning project designed to analyze banking customer behavior, identify financial trends, and segment customers for better decision-making.

---

## 📌 Project Overview

This project focuses on understanding customer financial behavior using real-world banking data. It combines:

- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Machine Learning (K-Means Clustering)  
- Interactive Power BI Dashboard  

---

## 🎯 Problem Statement

Banks need to understand:
- Who are their valuable customers?
- Which customers are risky?
- How do income, loans, and deposits relate?

This project answers these questions using data-driven insights.

---

## ⚙️ Tech Stack

- **Python** (Pandas, NumPy)
- **Visualization** (Matplotlib, Seaborn)
- **Machine Learning** (Scikit-learn - KMeans)
- **Power BI** (Dashboard & Reporting)

---

## 🧹 Data Preprocessing

- Removed unnecessary columns  
- Standardized column names  
- Converted date formats  
- Created new features:
  - Income Band (Low / Medium / High)
  - Age Group (Young / Middle / Senior)
  - Total Balance (Deposits + Savings + Checking)

---

## 📊 Exploratory Data Analysis (EDA)

### Key Visualizations:
- Income vs Loan (Scatter Plot)
- Loans by Income Band
- Correlation Heatmap
- Customer Distribution

### 🔍 Key Insights:
- Weak correlation between income and loans  
- Deposits strongly influence total balance  
- Low-income customers show higher financial risk  

---

## 🤖 Machine Learning (Customer Segmentation)

### Algorithm:
**K-Means Clustering**

### Steps:
- Feature Scaling using StandardScaler  
- Elbow Method to find optimal clusters (k = 4)

### 🎯 Segments Identified:

| Segment        | Description |
|----------------|------------|
| VIP            | High income & high deposits |
| High Risk      | High loans relative to income |
| Conservative   | High income but low loans |
| Low Value      | Low income & low activity |

---

## 📊 Power BI Dashboard

### 📌 Pages Included:

#### 1. Overview
- KPIs (Customers, Loans, Deposits, Balance)
- Income vs Loans
- Age Distribution

#### 2. Loans Analysis
- Loan trends
- Loan distribution
- Income vs Loan behavior

#### 3. Deposits Analysis
- Deposit trends
- Account type breakdown
- High-value customers

#### 4. Customer Analysis
- Age & Gender distribution
- Income segmentation
- Occupation insights

#### 5. Segmentation
- Customer clusters
- Segment value comparison
- Loan vs Deposit behavior

#### 6. Settings Panel
- Filters (Income, Gender, Segment)
- Navigation buttons
- Reset functionality

---



## 📈 Business Insights

- Income alone does not define loan behavior  
- Deposits are the strongest indicator of customer value  
- Low-income customers are relatively higher risk  
- Customers use multiple banking services → cross-selling opportunity  
- Segmentation helps in targeted marketing  

---

## 🚀 Future Improvements

- Add loan default prediction model  
- Use advanced clustering techniques  
- Deploy dashboard on Power BI Service  
- Real-time data integration  

---

## 💡 Conclusion

This project demonstrates how data analytics and machine learning can be combined to generate meaningful business insights and improve decision-making in the banking domain.

---

## 🔗 Connect With Me

If you found this useful or have suggestions, feel free to connect!
