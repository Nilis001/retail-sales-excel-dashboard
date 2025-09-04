# Retail Sales Excel Dashboard (Istanbul Malls, 2021–2023)

**Tools:** Excel (Power Pivot, PivotTables, Slicers, Conditional Formatting)  
**Files:**  
- `Retail_Sales_Dashboard_Istanbul.xlsx` (full workbook)  
- `Retail_Sales_Dashboard_Istanbul.pdf` (one-page dashboard)  
- PNGs: charts for quick preview

## Dataset
Customer shopping data from Istanbul malls (2021–2023), 99,457 rows, 10 columns  
Columns: invoice_no, customer_id, gender, age, category, quantity, price, payment_method, invoice_date, shopping_mall.  
Source: Kaggle (CC0 / Public Domain).

## Business Questions Answered
1. Which malls generate the highest total sales?  
2. Which product categories and payment methods dominate revenue?  
3. How do age groups contribute to sales mix?  
4. What is the month-over-month sales trend (2021–2023)?

## Method
- Created calculated column **TotalSales = Quantity × Price**  
- Cleaned `invoice_date` to proper Date type (DMY), added a monthly trend line  
- PivotTables for: Sales by Mall, Category, Payment Method, Age Group × Category (heatmap)  
- Slicers for **Shopping Mall** and **Age Group** to filter all visuals  
- Exported dashboard to PDF and screenshots for quick viewing

## Key Insights (examples)
- **Mall of Istanbul** leads total revenue across 2021–2023.  
- **Clothing** and **Shoes** are the top-grossing categories; **Credit Card** is the dominant payment method.  
- Sales are strongest among **30–49** age groups; **Under 20** contributes the least.  
- Clear seasonal bumps appear around year-end months.

## How to Use
- Open the `.xlsx` file → go to **Dashboard** sheet  
- Use the **Slicers** (Shopping Mall, Age Group) to filter all charts dynamically

## Skills Demonstrated
Excel data cleaning • PivotTables • Slicers • Conditional formatting heatmap • Chart design • KPI layout • Dashboard storytelling
