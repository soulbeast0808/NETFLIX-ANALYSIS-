# 🎬 Netflix Data Analysis Project

## 📌 Overview
This project is an end-to-end data analytics project based on the Netflix dataset.
The goal is to analyze content trends, understand distribution patterns, and generate meaningful insights using Python, SQL, and Power BI.

---

## 🎯 Objectives:

- Analyze the distribution of Movies vs TV Shows
- Identify trends in content release over the years
- Find top countries producing Netflix content
- Discover most popular genres
- Build an interactive dashboard for insights

---

## 🛠️ Tools & Technologies:

- 🐍 Python (Pandas, NumPy, Matplotlib, Seaborn)
- 🗄️ SQL (MySQL)
- 📊 Power BI (Dashboard & Visualization)

---

## 🔄 Project Workflow

### 1. Data Collection
- Dataset: Netflix dataset (CSV format)

### 2. Data Cleaning (Python)
- Handled missing values
- Converted data types
- Extracted numeric values from duration
- Created new columns like `duration_num`

### 3. Data Analysis (SQL)
- Performed aggregation using GROUP BY
- Analyzed content by type, country, and year
- Extracted key insights using SQL queries

### 4. Data Visualization (Power BI)
- Built interactive dashboard
- Created KPI cards (Total Titles, Movies, TV Shows)
- Used charts (Line, Bar, Pie)
- Added slicers for interactivity

---

## Key Insights
- Movies dominate Netflix content compared to TV Shows
- Significant growth in content after 2015
- United States produces the highest content
- Drama and Comedy are the most common genres

---

## 📁 Project Structure

Netflix-Analysis/
│
├── data/
│   ├── raw/
│   │   └── netflix.csv
│   │
│   └── processed/
│       └── netflix_cleaned.csv
│
├── python/
│   └── data_cleaning.ipynb
│
├── sql/
│   ├── schema.sql
│   └── analysis_queries.sql
│
├── powerbi/
│   └── netflix_dashboard.pbix
│
├── images/
│   └── dashboard.png
│
├── README.md
└── requirements.txt
