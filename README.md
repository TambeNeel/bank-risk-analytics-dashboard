# 🏦 Banking Risk Analytics Dashboard

A data analytics project designed to empower banking decision-makers with insights into client risk, loan performance, and deposit behavior using Power BI and Python.

---

## 📌 Problem Statement

Develop a basic understanding of risk analytics in banking and financial services. Use data to minimize the risk of loan defaults by identifying reliable clients based on historical and profile-based patterns.

---

## 🧩 Dataset Overview

The dataset contains multiple related tables:

- **Banking Relationship**
- **Clients - Banking**
- **Gender**
- **Investment Advisor**
- **Period**

📂 All datasets are located inside the `/data` folder.

---

## 🔧 Data Cleaning & Feature Engineering

Performed in both Power BI and Python:

- Created **Engagement Timeframe** and **Engagement Days**
- Binned **Estimated Income** into income bands
- Engineered **Processing Fees** based on fee structure
- Joined multiple CSVs using primary/foreign keys

---

## 📊 Power BI Dashboard

Developed a detailed Power BI dashboard with the following KPIs:

- Total Clients
- Total Loans
- Total Deposits
- Total Fees
- Account-wise breakdown (Savings, Checking, Foreign Currency, etc.)
- Loan and Deposit Analysis
- Summary View

🖥️ Dashboard file: `dashboard/Banking Dashboard.pbix`

---

## 📒 Jupyter Notebook (EDA)

The notebook `BankEDA.ipynb` includes:

- Exploratory data analysis (EDA)
- Null value handling
- Basic visualizations and distributions
- Dataset insights to assist in dashboard development

---

## 📈 Key DAX Measures Used

- `SUM`
- `DISTINCTCOUNT`
- `SUMX`
- `SWITCH`
- `DATEDIFF`


---

## 🚀 Future Enhancements

- Incorporate customer churn prediction using ML models
- Automate Power BI report updates using Power Automate
- Expand dashboard to include demographic segmentation analysis

---

## 🧠 Tools Used

- Power BI
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Microsoft Excel

---

## 🙌 Contributing

Feel free to fork this repo and submit PRs for improvement!

---

## 📬 Contact

For questions or feedback, feel free to reach out via GitHub Issues.

