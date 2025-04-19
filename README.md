# ☕ Coffee Sales Analysis (Excel Project)
## 📌 Project Overview
This project analyzes a coffee shop's sales data using Microsoft Excel. The goal was to uncover sales patterns and generate a dynamic dashboard that tracks key performance metrics such as revenue, transaction counts, peak hours, and popular drinks.

## 🔍 Objectives  
- Perform data cleaning and transformation for analysis readiness  
- Add a primary key column for row-level identification  
- Create calculated columns for month, weekday, and hour from datetime  
- Generate descriptive statistics using pivot tables  
- Visualize key metrics using Excel charts  
- Build an interactive dashboard with slicers for filtering

## 📊 Dataset Summary
- **Source:** to be included
- **Fields Included:**
  - Date, Time
  - Payment Method
  - Card Info
  - Amount Paid
  - Type of Drink

## 🔄 Data Cleaning & Transformation Steps  
The following transformations were performed before analysis:

1. **Added a Primary Key**  
   - Used the `ROW()` function to assign a unique ID to each record.

2. **Checked for Spelling & Typos**  
   - Ran Excel's spell check and manually verified column names and categories.

3. **Checked Extra Spaces**  
   - Used Find & Replace to look for extra spaces and clean inconsistent spacing, ensuring uniform text entries.

4. **Verified Absence of Duplicate Records**  
   - Used Excel’s `Remove Duplicates` feature to ensure uniqueness.

5. **Standardized Text Case**  
   - Applied functions like `UPPER()` and `PROPER()` for consistency.

6. **Standardized Date Formats**  
   - Reformatted dates for uniformity .

7. **Audited for Outliers & Errors**  
   - Used filters and conditional formatting to detect data anomalies.

8. **Extracted Time-Based Dimensions**  
   - Used the `MONTH()`, `TEXT()`, `WEEKDAY()`, and `HOUR()` functions to create columns:
     - Month
     - Weekday
     - Hour of the Day
To uncover time-based patterns in sales.

## 📊 Data Analysis 

Created the following pivot tables to categorize and summarize the data:

- **Month by Revenue** – Summarizes total revenue earned per month.  
- **Month by Transaction Count** – Counts the number of transactions per month to analyze purchasing patterns.  
- **Weekday by Transaction Count** – Identifies the busiest days of the week based on the number of transactions.  
- **Hour of Day by Transaction Count** – Reveals peak hours during the day when the coffee shop receives the most customers.  
- **Type of Drink by Amount Paid & Transaction Count** – Highlights the most popular drinks based on total revenue and number of transactions.  

## 📈 Dashboard Features  

Visualizations were created using **Pivot Charts** for dynamic interaction and real-time updates based on slicer selections.

- **Monthly Revenue** – Pivot Line Chart showing total revenue by month  
- **Transaction Volume** – Pivot Column Charts displaying:  
  - Transactions per month  
  - Transactions by day of the week  
  - Transactions by hour of the day  
- **Top Drinks** – Pivot Table visual showing drink types by total revenue and number of transactions  
- **Slicer** – Enables filtering dashboard visuals by type of drink  

## 🔧 Tools Used  
- Microsoft Excel  
  - Pivot Tables  
  - Data Cleaning Techniques  
  - Charts & Slicers

## 💡 Key Insights  
- March generated the highest revenue at $17,036, followed closely by October ($13,891) and February ($13,215). January recorded the lowest sales.
- Mondays and Tuesdays were the busiest weekdays regarding sales transactions, while Sunday was the slowest.
- Sales transactions rose significantly from 8 AM to 9 AM and peaked at 10 AM. The lowest activity occurred at 6 AM, 7 AM, and 10 PM.
- Latte generated the most revenue among all drink types.($ 27,866)
- Americano with Milk was the most popular drink based on the number of sales transactions.
- Espresso ranked lowest in both transaction count and total revenue
- Card payments accounted for 97.2% of all sales, while cash payments made up 2.76%.

## Recommendations
- Offer promotional deals on Sundays and early mornings (especially 6 AM to 8 AM) to boost traffic during low-activity periods.
- Introduce “morning bundles” or time-limited offers around 10 AM to capitalize on the peak transaction hour.
- Highlight Lattes and Americanos with Milk in special promotions since they lead in revenue and transaction count, respectively.
- Reevaluate the Espresso offering—consider rebranding, bundling, or replacing it due to its low popularity.
- Leverage high card usage (97.2%) by introducing digital loyalty programs or discounts for contactless payments.
   
## 📂 Project Files
- [📈 Coffee Sales Dataset (CSV)](data_raw/coffee%20sales%20dataset.csv)
- [📊 Coffee Sales Analysis Dashboard (XLSX)](data_clean/coffee%20Sales%20Analysis%20dashboard.xlsx)

  

