#  Product Insights Analytics Dashboard

An end-to-end Data Analytics and Business Intelligence project built using Python, Machine Learning, and Power BI.

This project focuses on analyzing product-related data to generate meaningful business insights related to pricing, customer ratings, stock behavior, and product demand.

---

#  Project Overview

The project demonstrates the complete analytics lifecycle:

1. Web Scraping & Data Collection
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Machine Learning Model Building
5. Power BI Dashboard Development
6. AI-Based Insights & Advanced Features

The final solution provides interactive dashboards and data-driven business recommendations.

---

#  Problem Statement

Businesses often struggle to understand:

* Product pricing behavior
* Customer rating patterns
* Inventory management
* High-demand product segments
* Overpriced product categories

This project aims to solve these problems using data analytics and visualization techniques.

---

#  Technologies Used

## Python Libraries

* Pandas
* NumPy
* BeautifulSoup
* Requests
* Seaborn
* Matplotlib
* Scikit-learn

## Power BI Features

* KPI Cards
* Scatter Charts
* Clustered Bar Charts
* AI Key Influencers Visual
* Sync Slicers
* Drill-through
* Role-Level Security (RLS)
* Bookmarks & Navigation

---

#  Web Scraping & Data Collection

The dataset was collected using Python-based web scraping techniques.

## Extracted Features

* Product Category
* Price
* Rating
* Stock Count
* Price Band
* Rating Level
* Stock Pressure

The extracted data was stored in CSV format for further preprocessing.

---

#  Data Cleaning & Preprocessing

The raw dataset contained:

* Duplicate values
* Inconsistent category names
* Formatting issues
* Invalid entries

## Cleaning Steps Performed

* Removed duplicates
* Handled missing values
* Standardized formats
* Fixed inconsistent category values
* Created derived columns
* Validated data quality

## Feature Engineering

New analytical features were created:

* Price Band
* Rating Level
* Stock Pressure
* Cluster Labels

---

#  Exploratory Data Analysis (EDA)

EDA was performed to uncover trends and hidden patterns.

## Key Analysis Performed

* Price Distribution Analysis
* Rating Analysis
* Stock Distribution Analysis
* Price vs Rating Relationship
* Category-wise Pricing Trends
* Cluster-wise Product Behavior

## Key Insights

* Lower-priced products often had better ratings.
* High-demand products generated higher stock pressure.
* Overpriced products showed lower customer satisfaction.
* Balanced products maintained strong overall performance.

---

#  Machine Learning Model

## Model Used

K-Means Clustering

## Product Clusters Identified

1. Balanced Products
2. Budget Products
3. High Demand Products
4. Overpriced Products

## Cluster Insights

### Balanced Products

* Strong ratings
* Stable stock levels
* Consistent customer satisfaction

### Budget Products

* Lower prices
* Moderate ratings
* Budget-friendly segment

### High Demand Products

* High stock pressure
* Lower inventory availability
* Strong customer demand

### Overpriced Products

* Higher prices
* Lower customer ratings
* Pricing optimization required

---

#  Power BI Dashboard

The project includes multiple interactive dashboard pages.

## Dashboard Pages

### 1. Main Dashboard

* Overall KPI overview
* Cluster distribution
* Product insights

### 2. Price Analysis Dashboard

* Price Band Distribution
* Average Price by Category
* Price vs Rating Analysis

### 3. Stock Analysis Dashboard

* Stock Distribution by Category
* Demand Pressure Analysis
* Stock vs Price Visualization

### 4. Cluster Analysis Dashboard

* Cluster Comparison
* Product Segmentation
* Cluster Performance Analysis

### 5. AI Insights Dashboard

* Key Influencers Visual
* AI-generated business insights

---

#  Advanced Power BI Features

## Implemented Features

* Sync Slicers
* Drill-through Pages
* Role-Level Security (RLS)
* Bookmark Navigation
* Interactive Filtering
* AI Key Influencers Visual

---

#  AI Insights

Power BI AI visuals identified major influencing factors affecting:

* Product Ratings
* Stock Pressure

## AI Findings

* Balanced Products increased average ratings.
* Good Rating Levels contributed to higher stock pressure.
* High Demand Products generated the strongest inventory pressure.

---

#  Business Recommendations

Based on the analysis:

* Improve inventory planning for high-demand products.
* Optimize pricing for overpriced products.
* Promote balanced products with strong customer satisfaction.
* Use stock pressure insights for demand forecasting.
* Monitor low-stock products proactively.

---

#  Project Structure

Product-Insights-Analytics/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   ├── web_scraping.ipynb
│   ├── data_cleaning.ipynb
│   ├── eda_analysis.ipynb
│   └── clustering_model.ipynb
│
├── powerbi/
│   └── Product_Insights_Dashboard.pbix
│
├── report/
│   └── Final_Project_Report.docx
│
├── presentation/
│   └── Project_Presentation.pptx
│
└── README.md
```

---

#  Final Outcome

This project successfully demonstrates:

✅ End-to-end Data Analytics Workflow
✅ Web Scraping & Data Processing
✅ Exploratory Data Analysis
✅ Machine Learning Clustering
✅ Interactive Power BI Dashboarding
✅ AI-Based Business Insights

The final dashboard converts raw product data into actionable business intelligence.

