# Data-Analyst-Project-using-Excel-Python-SQL-Power-BI


# 📊 Retail Sales Analytics | End-to-End ETL Pipeline

## 📌 Project Overview

This project demonstrates an end-to-end Data Analytics workflow by transforming raw Excel sales data into an interactive Power BI dashboard.

The pipeline includes:

Excel → Python → MySQL → SQL → Power BI

The project showcases data cleaning, transformation, database loading, SQL integration, and dashboard development to generate business insights.

---

## 🚀 Project Workflow

```
Raw Excel Data 
        │
        ▼
Python (Pandas)
• Load Dataset
• Remove Duplicates
• Fix Date Format
• Handle Missing Values
• Feature Engineering
        │
        ▼
Cleaned CSV
        │
        ▼
MySQL Database
        │
        ▼
Power BI Dashboard
        │
        ▼
Business Insights
```

---

## 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Data Cleaning & Transformation |
| Pandas | Data Manipulation |
| MySQL | Data Storage |
| SQLAlchemy | Database Connection |
| PyMySQL | MySQL Connector |
| Power BI | Dashboard & Visualization |
| Excel | Raw Dataset |

---

# 📂 Project Structure

```
Retail-Sales-Analytics

│
├── data
│     sales_raw_500.xlsx
│     sales_cleaned.csv
│
├── notebooks
│     data_cleaning.ipynb
│     mysql_upload.ipynb
│
├── dashboard
│     Retail Dashboard.pbix
│
├── images
│     dashboard.png
│
└── README.md
```

---

# ⚙️ ETL Process

## Step 1 — Load Raw Excel Data

- Imported dataset using Pandas
- Loaded Excel file

```python
pd.read_excel()
```

---

## Step 2 — Data Cleaning

Performed:

- Removed duplicate records
- Standardized date format
- Removed invalid dates
- Fixed missing values

---

## Step 3 — Feature Engineering

Created new business columns

- Profit
- Year
- Month

These columns improve reporting and dashboard analysis.

---

## Step 4 — Export Clean Dataset

Saved cleaned dataset as

```
sales_cleaned.csv
```

---

## Step 5 — Load into MySQL

Connected Python with MySQL using

- SQLAlchemy
- PyMySQL

Loaded data into

```
sales_data
```

table.

---

## Step 6 — Power BI Dashboard

Built an interactive dashboard including:

✔ Sales Trend

✔ Profit by Region

✔ Product Performance

✔ Region Filters

✔ Year Filters

✔ KPI Cards

---

# 📈 Dashboard Preview

(Add your dashboard screenshot here)

```markdown
![Dashboard](images/dashboard.png)
```

---

# 📊 Dashboard Features

- Total Profit KPI
- Monthly Sales Trend
- Profit by Region
- Sales by Product
- Interactive Slicers
- Dynamic Filtering

---

# 💡 Key Learnings

Through this project I learned:

- ETL Pipeline Development
- Data Cleaning with Pandas
- Feature Engineering
- Loading Data into MySQL
- Connecting SQL with Power BI
- Building Interactive Dashboards

---

# 🔮 Future Improvements

- Add SQL analytical queries
- Create Star Schema
- Improve dashboard design
- Add DAX Measures
- Deploy using Power BI Service
- Automate ETL process

---

# 👨‍💻 Author

**Rahul Singh**

Aspiring Data Analyst

Skills: Python • SQL • Excel • Power BI • Git • GitHub

Python • SQL • Excel • Power BI • Git • GitHub
