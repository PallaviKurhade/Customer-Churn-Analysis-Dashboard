# Customer-Churn-Analysis-Dashboard

📌 Project Overview

This Power BI dashboard analyzes customer churn behavior and retention patterns. The dashboard helps businesses understand why customers leave, identify high-risk customers, and improve customer retention strategies through data-driven insights.

---

📷 Dashboard Screenshot

"Customer Churn Dashboard" <img width="1140" height="653" alt="Customer Churn DB" src="https://github.com/user-attachments/assets/ed503933-8eeb-4edb-aa8f-be4a6d538f9f" />


---

🎯 Business Problem

Customer churn is one of the biggest challenges for subscription-based businesses. High churn rates lead to revenue loss and increased customer acquisition costs.

This dashboard helps answer:

- Which customers are most likely to churn?
- How does contract type affect churn?
- What impact do services have on retention?
- Which customer segments need attention?

---

📊 Key KPIs

KPI| Value
Total Customers| 7043
Churn Rate| 26.54%
Churned Customers| 1869
Retained Customers| 5174

---

📈 Dashboard Features

Customer Retention Overview

- Retained vs Churned Customers
- Customer Risk Analysis

Contract-Based Churn Analysis

- Month-to-Month
- One Year
- Two Year

Tenure Analysis

- 0–6 Months
- 6–12 Months
- 12+ Months

Service Analysis

- Online Security Impact
- Backup Service Impact

Monthly Charges Analysis

- Retained vs Churned Customers

---

🛠 Tools & Technologies

- Power BI
- DAX
- Power Query
- Excel
- Data Modeling

---

📐 Sample DAX Measures

Total Customers =
COUNT(Customer[CustomerID])

Churned Customers =
CALCULATE(
    COUNT(Customer[CustomerID]),
    Customer[Churn] = "Yes"
)

Churn Rate =
DIVIDE([Churned Customers],[Total Customers])*100

---

🔍 Key Insights

- Month-to-Month customers contribute most to churn.
- Customers with lower tenure show higher churn rates.
- Online Security and Backup services improve retention.
- High-risk customers can be targeted with retention campaigns.

---

💼 Business Impact

This dashboard enables businesses to:

- Reduce customer churn
- Improve retention strategies
- Identify high-risk customers
- Increase customer lifetime value
- Make data-driven decisions

---







Aspiring Data Analyst | Power BI Enthusiast
