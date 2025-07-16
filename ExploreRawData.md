## 🔍 2. How to Explore Raw Data (Beginner-Friendly)
### ✅ 1. Look at the Columns (Fields)
#### Ask yourself:

What does each column mean?

Are they useful for analysis?

#### 📌 Example:
Date | Time | Product | Category | Quantity | Price | Total Sales | Customer ID
Check:

Are there columns with dates? You can explore time-based trends.

Are there sales amounts? You can calculate revenue.

Is there customer info? You can explore customer behavior.

### ✅ 2. Identify Data Types
Check what type of data each column contains:

Text – Product names, categories

Numbers – Quantity, Price

Dates – Sales date or time

👉 In Excel: Click on a column → Look at data type in the formula bar
👉 In Power BI: In Power Query Editor → Check the column icon

### ✅ 3. Look for Patterns
#### Ask:

What products are repeated often?

What dates have higher sales?

Are some categories more frequent?

# 🔎 Tip: Use Pivot Tables in Excel or Group By in Power BI to summarize and spot patterns.

### ✅ 4. Check for Missing or Incorrect Data
Any blank cells in important columns? (like Price, Quantity)

Any weird or impossible values? (like negative quantity, missing product names)

🛠 How:

In Excel: Use filters to check for blanks or errors

In Power BI: Use filters or sort columns in Power Query to find null values

### ✅ 5. Understand Granularity (Level of Detail)
#### Ask:

Is each row a single transaction?

Does each row represent daily totals?

Does it show per customer or just overall sales?

This shows transaction-level data — each row is one product sold.

### ✅ 6. Ask Basic Questions About the Data
Here are some questions to guide your exploration:

How many unique products are sold?

What’s the total revenue?

How many total transactions are there?

Which product was sold the most?

Which day had the highest sales?

🛠 Tip:

Use COUNT(), SUM(), AVERAGE() in Excel

Use GROUP BY in SQL or Power BI for summaries

🧾 Quick Checklist for Exploring Raw Data

|Task		                   | Excel Tool             | 	Power BI Tool                 |SQL Query/Tool  
|--------------------------|------------------------|--------------------------------|-----------------------------------------------------------------|
| View structure of data   | Scroll & review	      | Data view / Power Query Editor | DESCRIBE table_name; or SELECT * FROM table_name LIMIT 5;       | 
| Check column data types  | Format Cells	          |Column icons in Power Query	   |DESCRIBE table_name; or check schema in DB                       |
| Find missing values	     | Filter blanks	        | Filter for nulls	             |SELECT * FROM table_name WHERE column_name IS NULL;              |
| Summarize data	         | Pivot Tables	          | Group By / Visuals             |SELECT column, COUNT(*) FROM table_name GROUP BY column;         |
| Spot outliers or mistakes| Conditional Formatting	| Visual inspection / Filters    |SELECT * FROM table_name WHERE column > 10000; (adjust condition)|
| Count unique values	     | COUNTIF, UNIQUE()	    | DAX: DISTINCTCOUNT()           |SELECT COUNT(DISTINCT column_name) FROM table_name;              |
#### 
