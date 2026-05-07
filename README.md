# 📦 Olist Intelligence — E-Commerce Revenue & Customer Analytics Dashboard

> An interactive business intelligence dashboard built on the Brazilian Olist E-Commerce dataset (2016–2018), featuring RFM segmentation, delivery analytics, review insights, and CLV prediction.

🔗 **Live Demo:** [ecommerce-analytics-4mwf2myu4ggry9asvkcsii.streamlit.app](https://ecommerce-analytics-4mwf2myu4ggry9asvkcsii.streamlit.app/)

---

## 📊 Dashboard Overview

![Dashboard Preview](https://ecommerce-analytics-4mwf2myu4ggry9asvkcsii.streamlit.app/)

The dashboard analyses **99,441 delivered orders** across 5 interactive tabs, with real-time filters by customer state and year.

---

## ✨ Features

### 📈 Revenue Trends
- Monthly revenue area chart with 3-month rolling average
- Revenue breakdown by Brazilian state (top 10)
- Top 10 product categories by revenue
- Payment type distribution (credit card, boleto, voucher, debit)

### 👥 RFM Segmentation
- Recency · Frequency · Monetary scoring for every customer
- Automatic segmentation into Champions, Loyal Customers, At Risk, and Lost
- Revenue contribution per segment
- Segment deep-dive summary table

### 🚚 Delivery Analysis
- Delivery delay distribution (actual vs estimated)
- On-time vs late delivery pie chart
- Top 10 states with worst average delays
- Actionable carrier SLA insights

### ⭐ Review Insights
- Review score distribution (1–5 stars)
- Average delivery delay by review score
- Correlation between delivery speed and customer satisfaction

### 💎 CLV Prediction
- BG/NBD-inspired Customer Lifetime Value model
- 12-month projected CLV per customer
- CLV tier classification (High / Mid / Low Value)
- Churn probability estimation
- Top 20 highest-value customers table

---

## 🛠️ Tech Stack

| Layer | Tools |
|---|---|
| Language | Python 3 |
| Data Processing | Pandas, NumPy |
| Visualisation | Plotly Express, Plotly Graph Objects |
| Frontend | Streamlit |
| Deployment | Streamlit Cloud |
| Data Source | Kaggle · Olist Store |

---

## 📁 Dataset

This project uses the [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) from Kaggle.

| File | Description |
|---|---|
| `olist_orders_dataset.csv` | Order status and timestamps |
| `olist_order_items_dataset.csv` | Items per order with price & freight |
| `olist_customers_dataset.csv` | Customer location data |
| `olist_order_payments_dataset.csv` | Payment method and value |
| `olist_order_reviews_dataset.csv` | Customer review scores |
| `olist_products_dataset.csv` | Product category info |
| `olist_sellers_dataset.csv` | Seller state data |
| `product_category_name_translation.csv` | Portuguese → English category names |

---

## 🚀 Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/shivisharma2003/ecommerce-analytics.git
cd ecommerce-analytics

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the app
streamlit run app.py
```

> Make sure all CSV dataset files are in the same directory as `app.py`.

---

## 📌 Key Insights

- 💳 **Credit card** dominates at ~74% of transactions
- 🏙️ **São Paulo (SP)** accounts for ~42% of total revenue
- ⭐ **57%** of customers give 5-star reviews
- 🚚 Most orders arrive **early** — a strong competitive advantage
- 👑 **Champions** are only a small % of users but drive the majority of revenue

---

## 👤 Author

**Shivi Sharma**  
[GitHub](https://github.com/shivisharma2003) · [LinkedIn](https://www.linkedin.com/in/shivisharma2003)

---

*Built with ❤️ using Python & Streamlit*
