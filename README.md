# 📊 Swiggy Sales Analysis

## 📌 Project Overview

This project analyzes Swiggy sales data using Python to identify sales trends, customer patterns, regional performance, and key business metrics.

The dataset contains **197,430 records** and **10 features**.

The main goal of this project is to transform raw sales data into useful business insights through data analysis and visualization.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

---

## 📊 Key Performance Indicators (KPIs)

The following KPIs were calculated during the analysis:

| KPI | Result |
|---|---:|
| Total Sales | ₹53,012,505.77 |
| Total Orders | 197,430 |
| Average Order Value | ₹268.51 |
| Average Rating | 4.34 |
| Total Rating Count | 5,591,574 |

---

## 🔍 Analysis Performed

The project includes:

- Monthly Sales Trend
- Daily Sales Trend
- Weekly Sales Trend
- Total Sales by State
- Top 5 Cities by Sales
- Quarterly Performance Analysis
- Veg vs Non-Veg Revenue Analysis
- KPI Analysis

---

## 📈 Monthly Sales Trend

Monthly revenue was analyzed to understand how sales changed over time.

This analysis helps identify:

- Sales growth and decline
- Monthly performance
- Changes in customer spending over time

---

## 📅 Weekly Sales Trend

Weekly sales were calculated using the order date.

This allows us to monitor short-term changes in revenue and identify weeks with unusually high or low sales.

---

## 🌍 Sales by State

Sales were grouped by state to compare regional performance.

This analysis helps identify which states generate the highest revenue and where business performance may need improvement.

---

## 🏙 Top 5 Cities by Sales

The five cities with the highest total sales were identified using Python and visualized with Plotly.

This helps identify the strongest geographic markets.

---

## 📆 Quarterly Performance

Quarterly performance was evaluated using:

- Total Sales
- Average Rating
- Total Orders

This provides a high-level view of business performance across different quarters.

---

## 🍽 Food Category Analysis

Food items were classified into:

- Veg
- Non-Veg

Revenue contribution from both categories was then compared using a donut chart.

> Note: Food categories were derived from keywords in dish names, so this classification should be treated as an analytical approximation.

---

## 💡 Key Insights

- Total sales reached approximately **₹53.01 million**.
- The dataset contains **197,430 orders**.
- Average order value is approximately **₹268.51**.
- The average customer rating is **4.34**.
- Sales performance was analyzed across different time periods and geographic locations.
- State and city-level analysis helps identify high-performing markets.
- Weekly, monthly, and quarterly analysis provides different views of sales performance.

---

## 📂 Project Structure

```text
swiggy-sales-analysis/
│
├── swiggy-sales-analysis.ipynb
├── swiggy_data.xlsx
└── README.md

🚀 How to Run
1. Clone this repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Update the dataset path if necessary.
5. Run the notebook cells from top to bottom.
Required libraries:
pip install pandas numpy matplotlib seaborn plotly openpyxl

🎯 Project Objective
The objective of this project is to demonstrate practical skills in:
- Data Cleaning and Processing
- Exploratory Data Analysis
- KPI Calculation
- Time-Series Sales Analysis
- Data Visualization
- Business Data Analysis
👤 Author
Javohirxon Bashirov
Data Analysis | Python | SQL | Machine Learning
