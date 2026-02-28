# Customer Segmentation Analysis

##  Project Objective
Perform customer segmentation using RFM analysis and SQL-based behavioural insights to identify high-value customers and support data-driven marketing strategies.

---

## 📊 Dataset
Online Retail transactional dataset containing:
- Invoice information
- Product details
- Quantity and price
- Customer ID
- Country
- Transaction dates

---

## 🛠 Tools & Technologies
- Python (Pandas, NumPy)
- SQL (SQLite executed within Google Colab)
- Tableau (Dashboard Visualization)
- Matplotlib
- Google Colab

---

## 🔎 Analysis Performed

### SQL Behavioural Analysis
- Total revenue per customer
- Purchase frequency (distinct invoices per customer)
- Average order value (AOV)
- Monthly revenue trends
- Top-performing customers
- Revenue by country

### Python Analysis
- Data cleaning and preprocessing
- Handling missing Customer IDs
- Removing cancelled transactions
- RFM (Recency, Frequency, Monetary) segmentation
- Customer segment classification
- Exported segmented dataset for visualization

---

## 📊 Tableau Dashboard

The final RFM segmented dataset was exported from Python and visualized in Tableau to create an interactive dashboard.

### Dashboard Includes:
- KPI Cards (Total Revenue, Total Customers, AOV)
- Revenue by Customer Segment
- Segment Distribution
- Monthly Revenue Trend
- Top 10 Customers
- Revenue by Country Map

🔗 Tableau Public Link: (https://public.tableau.com/app/profile/mya.lwin/vizzes)

---

## 📈 Key Insights
- High-value customers contribute a significant share of total revenue.
- A large proportion of customers are one-time buyers, indicating retention opportunity.
- Revenue shows strong seasonality, peaking in Q4 (Nov–Dec).
- A small segment of customers drives disproportionate revenue contribution.

---

## 📂 Project Structure
- `notebooks/customer_segmentation.ipynb` → Full analysis
- `sql/queries.sql` → SQL behavioural queries
- `dashboard/` → Tableau workbook
- `data/online_retail.csv` → Dataset

---

## 🚀 Business Impact
This analysis enables:
- Targeted marketing campaigns
- Retention strategies for mid-tier customers
- Focused engagement with high-value customers
- Revenue optimization through behavioural segmentation
