# Customer Behavior Analysis Dashboard
> End-to-end data pipeline: Python → PostgreSQL → Power BI


## Project Overview

This project analyzes customer shopping behavior using a full data pipeline — from raw data processing in Python, storing and querying in PostgreSQL, to an interactive Power BI dashboard.

**Key insights surfaced:**
- 73% of customers are non-subscribers vs 27% subscribers
- Clothing & Accessories dominate both revenue and sales volume
- Young Adults and Middle-aged groups are the highest revenue segments
- Average purchase amount: $59.76 | Average review rating: 3.75

## Tech Stack

| Layer | Tool |
|-------|------|
| Data Processing | Python (Pandas, NumPy) |
| Database | PostgreSQL |
| Visualization | Power BI |
| Query Language | SQL |

## Pipeline

```
Raw Data (CSV)
    ↓
Python — data cleaning, EDA, preprocessing
    ↓
PostgreSQL — structured storage, SQL queries
    ↓
Power BI — interactive dashboard & visuals
```

## Dashboard Features

- **KPI Cards** — Total customers, Avg purchase amount, Avg review rating
- **Subscription breakdown** — Donut chart (Yes/No split)
- **Revenue & Sales by Category** — Clothing, Accessories, Footwear, Outerwear
- **Age Group Analysis** — Revenue and sales by Young Adult, Middle-aged, Adult, Senior
- **Filters** — Subscription status, Gender, Category, Shipping type

## How to Run

1. Clone the repo
   ```bash
   git clone https://github.com/YOUR_USERNAME/customer-behavior-analysis
   ```
2. Install Python dependencies
   ```bash
   pip install pandas numpy psycopg2 sqlalchemy
   ```
3. Run the Python script to process and load data into PostgreSQL
   ```bash
   python data_pipeline.py
   ```
4. Open `dashboard.pbix` in Power BI Desktop

## Dataset

- ~3,900 customer records
- Features: Age, Gender, Category, Purchase Amount, Subscription Status, Shipping Type, Review Rating

> Dataset source: [(https://www.kaggle.com/datasets/ayeshasiddiqa123/customer-shopping-behavior-dataset/data)]

## Author

Made by [Syeda Irram] — [LinkedIn](linkedin.com/in/iram-hassan) -> Inspiration from [(in/amlanmohanty1)]

Open to Data Analytics roles!
