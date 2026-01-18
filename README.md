# Olist Orders Delivery Analysis

## Project Overview
This project analyzes the **order lifecycle and delivery performance** of the Olist e-commerce dataset.  
The primary focus is on **delivery delays**, **order status distribution**, and **monthly delivery trends** to evaluate logistics efficiency and operational performance.

---

## Objectives
- Analyze order status distribution
- Identify delivered vs non-delivered orders
- Calculate delivery delays (actual vs estimated delivery)
- Classify deliveries as **Late** or **On-Time/Early**
- Measure late delivery rates over time
- Extract actionable insights from delivery performance

---

## Dataset
**Source:** Olist Brazilian E-Commerce Dataset  

**Primary file used:**
- `olist_orders_dataset.csv`

**Key columns analyzed:**
- `order_status`
- `order_purchase_timestamp`
- `order_delivered_customer_date`
- `order_estimated_delivery_date`

---

## Methodology
1. Data loading and structure validation  
2. Missing value and data quality checks  
3. Order status frequency and percentage analysis  
4. Filtering delivered orders for performance evaluation  
5. Delivery delay calculation (actual − estimated)  
6. Classification of delivery performance  
7. Monthly aggregation of late delivery rates  

---

## Key Insights
- More than **97% of orders** are successfully delivered.
- A noticeable portion of delivered orders arrive **after the estimated delivery date**.
- Delivery delays vary across months, indicating **seasonal or operational constraints**.
- Late delivery rate analysis provides a clear metric for logistics performance tracking.

---

## Output
- Clean, reproducible Jupyter Notebook
- Delivery delay metrics and classifications
- Monthly late delivery rate analysis
- Business-ready insights for operations evaluation

---
## Project Structure
<img width="388" height="388" alt="image" src="https://github.com/user-attachments/assets/0d981bc6-63c3-4549-b1e2-c0d932cb8147" />

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Next Steps
- Integrate order items and payment datasets
- Analyze revenue impact of delivery delays
- Compare late delivery rates across customer regions
- Extend analysis to seller-level delivery performance



## Project Structure
