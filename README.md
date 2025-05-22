# 📊 Financial Statements Analysis Report – ZoomCharts Challenge

This Power BI report was built as an entry for the **ZoomCharts Financial Statement Reporting & Analysis Challenge**. It visualizes actual vs. budgeted financials for a fictional SaaS company and helps stakeholders understand the story behind the numbers.

---

## 📁 Dataset Overview

The dataset contains 3 core tables:

- **Transaction** – Actual income and expense records
- **Budget** – Budgeted/planned financial figures
- **Accounts** – Account hierarchies and classifications

Each record includes:
- Date, account codes
- Account classification (G&A, S&M, etc.)
- Transaction type, client/vendor name
- Revenue/Expense flag
- Amounts (actual/budget)

---

## 📘 Report Structure

### 🧭 **Page 1: Revenue & Expense Overview**
This page features a dynamic parameter-based switch that lets users toggle between Revenue and Expense metrics across all visuals:
- KPI cards: Total amount, number of transactions, total budget, profit/loss, variance
- Timeline trend (ZoomCharts): Actuals vs Budget vs Variance across quarters/months
- Revenue/Expense by Name (Top Clients or Vendors)
- Monthly performance trend
- Matrix by Name and Quarter

🎯 *Insight*: Track key performance indicators and client/vendor contributions over time.

---

### 🧭 **Page 2: Budget Performance & Accuracy**
Drill into budget alignment and financial efficiency:
- KPI cards: Profit/Loss, Budget Accuracy Rate, Variance %
- Budget Accuracy by Class → Account → Name
- Profitability by Class
- ZoomChart Timeline for Budget Variance over time
- Scatter plot: Budget Accuracy vs Variance SD

🎯 *Insight*: Identify consistent over/under budget accounts, accurate departments, and variance outliers.

---

### 🧭 **Page 3: Variance Drivers & Trends**
This page uncovers underlying contributors to variance and how they trend over time:
- KPI cards: Avg Transaction Value, % of Total Budget, Variance SD
- QoQ Growth of Actual, Budget, and Variance
- Matrix Table: Conditional formatting by Over/Under budget, Profit/Loss
- Variance by Memo/Description
- Variance contribution by Name & Class with ZoomCharts donut/bar

🎯 *Insight*: Uncover causes of budget misalignment and spot consistent overrun categories.

---

## 🧮 Key Measures

- `Revenue Amount`, `Expenses Amount`, `Revenue Budget`, `Expenses Budget`
- `Profit/Loss` = Revenue – Expenses
- `Variance` = Actual – Budget
- `Budget Accuracy Rate` = 1 - ABS(Actual - Budget) / Budget
- `Variance SD` (Standard Deviation of Variance by group)
- `Average Transaction Value`
- `QoQ Change` = (Current Q - Previous Q) / Previous Q

---

## 🧰 Tools & Visuals

- **Power BI**
- **ZoomCharts Drill Down Visuals**
- Parameterized selectors for toggling view modes
- Dynamic matrices, trendlines, and scatter analysis
- Conditional formatting for variance heat maps

---

## 🎨 Design & Theme

- **Background**: #F4F4F4 (light neutral)
- Accent Colors:
  - Revenue: #2E86C1
  - Expenses: #1ABC9C
  - Positive: #27AE60
  - Negative: #C0392B

---

## 📎 How to Use

1. Open the `.pbix` file in Power BI Desktop
2. Use the **measure selector slicer** to toggle between Revenue/Expense
3. Interact with ZoomChart visuals to drill down from Quarter → Month → Day
4. Click on any visual to filter the full report contextually

---

## 🏆 Why It Stands Out

- Fully parameter-driven visuals and matrix tables
- Storytelling built into every page
- High-performance DAX and clean UX
- Focused on practical financial decisions and budget control

---

## 💬 Feedback & Collaboration

Have feedback or ideas to improve this report? Open an issue or connect with me on [LinkedIn](https://www.linkedin.com/in/emmanuel-idowu-analyst/).

---

**Made by Emmanuel Idowu**  


