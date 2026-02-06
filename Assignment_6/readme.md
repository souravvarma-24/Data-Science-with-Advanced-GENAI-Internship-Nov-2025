# Domino’s Store Delivery Time Analysis

## 📖 Project Overview
This project analyzes pizza delivery times for a Domino’s franchise store to evaluate whether the store meets the company’s operational performance benchmark.

Domino’s requires that the **95th percentile of order delivery time remains below 31 minutes**. Failure to meet this criterion may lead to penalties, including potential loss of franchise privileges.  
The objective of this analysis is to assess delivery performance and provide actionable, data-driven insights to support informed business decisions.

This work is a **business analytics case study**, focused on performance evaluation rather than predictive modeling.

---

## 🧩 Business Problem
Kanav, the store owner, operates the pizza outlet 24×7 to maximize revenue and customer reach.  
Domino’s has informed him that store performance will be evaluated based on delivery efficiency, specifically:

- **95% of all orders must be delivered within 31 minutes**

Kanav requires a clear understanding of his store’s delivery behavior to:
- Evaluate compliance with the benchmark
- Identify operational risks
- Take corrective actions to protect the business

---

## 📊 Dataset Description
The dataset contains delivery-time records for individual pizza orders.

Key column used in the analysis:
- **Delivery Time**: Total time (in minutes) taken to deliver an order

Each row represents a single completed order.

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🔍 Analysis Performed
The analysis includes:

- Exploratory Data Analysis (EDA) of delivery times
- Distribution analysis to understand overall delivery behavior
- Percentile-based evaluation with emphasis on the 95th percentile
- Comparison of observed performance against the 31-minute threshold
- Visualization of delivery-time spread and extreme delays

---

## 📈 Key Insights
- Delivery times show noticeable variability rather than uniform performance
- The 95th percentile provides a more realistic risk indicator than average delivery time
- A small number of delayed orders significantly affect compliance with the benchmark
- Operational risk is primarily driven by extreme cases rather than typical deliveries

(Detailed interpretations and visual evidence are provided within the notebook.)

---

## ✅ Conclusion
This analysis enables an objective evaluation of whether the store meets Domino’s delivery-time requirements.  
By focusing on high-percentile delays, the store owner can target specific operational bottlenecks and improve service reliability while reducing business risk.

---

## 📁 Files in This Repository
- `Task 2 - Diminos Case Study.ipynb` → Complete analysis notebook
- `diminos_data.csv` → Dataset used for analysis
- `README.md` → Project documentation

---

If this repository helps in understanding percentile-based performance analysis, a GitHub star can be used as a form of appreciation or feedback.
