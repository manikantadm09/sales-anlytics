# Restaurant Sales Analytics – Data Analyst Case Study

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)](https://pandas.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview
This project analyzes restaurant POS transaction data to understand **revenue drivers, pricing effectiveness, product performance, and customer behavior**.  
The analysis is designed to support **business and operational decision-making** using data analytics and dashboards.

---

## Dataset
- 50,000+ restaurant transactions
- Format: Excel (.xlsx)
- Key fields: order time, items, category, price, discounts, payment method, service area

---

## Dashboards & Insights

### 1. Executive Business Overview
![Executive Overview](screenshots/executive_overview.png.png)

**Insights**
- Total revenue of ₹6.84M with a profit margin of 7%
- Revenue peaks during lunch (1–3 PM) and dinner (7–9 PM)
- Discounts account for ~14% of gross revenue, impacting profitability

---

### 2. Product & Pricing Analytics
![Product & Pricing](screenshots/product_pricing_analytics.png.png)

**Insights**
- Non-Veg Biryani is the highest revenue-generating category
- A small group of top items contributes a disproportionate share of sales
- Higher discounts do not consistently lead to proportional revenue growth

---

### 3. Time & Customer Insights
![Time & Customer](screenshots/time_customer_insights.png.png)

**Insights**
- Order volume spikes align with staffing-intensive hours
- Online and UPI-based payments dominate transactions
- Aggregator platforms (Zomato, Swiggy) drive a significant portion of orders

---

## Tools & Technologies
- **Python:** Pandas, NumPy
- **Visualization:** Power BI, Plotly
- **Environment:** Jupyter Notebook
- **Version Control:** Git & GitHub

---

## Business Value
This analysis helps restaurants:
- Identify high-impact products and pricing opportunities
- Optimize staffing using peak-hour demand patterns
- Understand customer behavior across payment methods and channels

---

## How to Run
```bash
git clone https://github.com/manikantadm09/sales-analytics.git
cd sales-analytics
pip install -r requirements.txt
jupyter notebook Restaurant_Sales_Analysis.ipynb


---

### 🔧 ADD THIS AT THE END (MANDATORY)

```md
---

## Author
**Manikanta DM**  
Email: manikantadm.25@gmail.com  
GitHub: https://github.com/manikantadm09  
LinkedIn: https://linkedin.com/in/manikantadm09  

---

## License
MIT License
