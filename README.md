# 🍫 Chocolate Company Sales Performance Dashboard - Power BI

This repository contains a Power BI dashboard developed to analyze and visualize the sales performance of a chocolate company. The dashboard leverages data from two CSV files — actual sales and target sales by salespersons — to provide actionable insights into sales performance, variance, and future trends.

## 📊 Project Overview

The dashboard answers key business questions and showcases advanced Power BI capabilities, such as unpivoting columns, data cleaning, custom visuals, and forecasting.

### 🔍 Business Questions Answered

1. **Actual Performance by Product, Person, and Team**  
   Visualizes sales performance across different dimensions to evaluate efficiency and top performers.

2. **Variance Analysis by Salesperson (Overall)**  
   Compares actual sales against targets to identify underperformers and overachievers.

3. **Monthly Variance Leader**  
   Identifies the salesperson with the highest variance (positive or negative) in each month.

4. **Most Profitable Products**  
   Analyzes product profitability to highlight which products yield the highest profit per box.

5. **Sales Forecast for the Next 3 Months**  
   Uses Power BI’s built-in forecasting model to predict future sales trends.

---

## 📁 Data Sources

- **`actuals.csv`** – Contains data on actual sales made by each salesperson.
- **`targets.csv`** – Contains sales targets assigned to each salesperson.

---

## 🛠 Power BI Features & Techniques Used

- **Data Preparation**
  - Unpivoted columns for better analysis
  - Removed duplicates and formatted data types
  - Referenced columns for consistent transformation logic

- **Data Modeling**
  - Created relationships between tables for accurate calculations
  - Added calculated columns and custom measures (e.g., variance, profit per box)

- **Visualization**
  - Created dynamic charts and KPIs
  - Customized report themes and layouts for clarity and branding

- **Forecasting**
  - Leveraged Power BI’s forecasting tool for predictive insights

    ![Screenshot 2025-04-13 002051](https://github.com/user-attachments/assets/a73659f9-7c5c-408e-977e-4b5f422f25f0)


## 📷 Dashboard Preview
![Screenshot 2025-04-12 231816](https://github.com/user-attachments/assets/d7047b23-e9d8-48c1-ae9c-47286d691ded)
![Screenshot 2025-04-12 234510](https://github.com/user-attachments/assets/a55987b1-3fd1-4d0e-88e1-40b48098655e)

## 🚀 How to Use

1. Download or clone this repository.
2. Open the Power BI `.pbix` file.
3. Load the provided CSV files or connect to your own dataset with the same structure.
4. Explore the dashboard to interact with the insights.

## 🤝 Contributions
Feel free to fork this repo, suggest improvements, or reach out if you’d like to collaborate.
