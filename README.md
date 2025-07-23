# Banking_Analytics
This Power BI project is built using a simulated financial dataset containing information on cards, transactions, and users. It presents a comprehensive analytical solution for a banking environment.
# 🏦 Power BI Banking Analytics Dashboard

This project provides a comprehensive **Power BI dashboard solution** built on a simulated banking dataset. It aims to support **fraud detection**, **customer insights**, **financial forecasting**, and **business intelligence** through advanced data modeling and interactive visualizations.

---

## 📁 Dataset Overview

The solution is based on three relational tables:

1. **cards_data**  
   - Card details: brand, type, chip status, credit limit, card on dark web, etc.

2. **transactions_data**  
   - Transaction-level data: card ID, chip usage, errors, merchant details, etc.

3. **users_data**  
   - User demographics: age, gender, income, location, credit score, debt, etc.

---

## 📊 Dashboards

### 🔐 1. Fraud Detection & Security
- Non-chip vs chip transactions
- Invalid transaction attempts (CVV, PIN, expiry issues)
- Cards exposed on the dark web
- Fraudulent transactions by account age and card limit

### 👥 2. Customer Analytics
- Segmentation by credit score, income, age, and account age
- Total number of credit cards by demographic groups
- Geographical mapping of users and behavior patterns

### 📈 3. Financial Planning & Forecasting
- Forecasted monthly spending
- Credit utilization and debt-to-income analysis
- Funnel analysis: Age → Retirement → Card Ownership → Debt Load

### 💼 4. Business Intelligence
- KPI cards (Total users, suspicious transactions, fraud attempts)
- Binned visualizations (Income, Credit Score, Account Age)
- Transaction trends and usage analysis by user and card segments

---

## 🧠 Key Features

- **Advanced DAX** for calculated measures and filtering logic
- **Row and filter context** management for accurate computations
- **Custom bins** and segments for income, credit score, and account age
- **Data model relationships** (many-to-one, directionally filtered)
- **Interactive slicers** to explore by gender, card type, location, etc.

---

## 🚀 Getting Started

1. Open the `.pbix` file in Power BI Desktop.
2. Connect/refresh the model if needed.
3. Explore each dashboard using slicers and tooltips.
4. Use DAX formulas provided in the model to learn advanced logic.

---

## 🛠 Tools Used

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Relational data modeling**

---

## 📌 Use Cases

- Real-time fraud risk tracking
- Strategic customer segmentation
- Financial behavior forecasting
- Enhanced reporting for banking stakeholders

---

## 🧾 License

This project is for **educational and portfolio use** only.  
All data is **synthetic** and does not contain real personal or financial information.
**screenshot**
https://github.com/abirpython300/Banking_Analytics/blob/main/FA.PNG


---

## 🙌 Acknowledgements

Special thanks to mentors and the data analytics community for ongoing support and learning.

---
