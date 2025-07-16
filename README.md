# 🔍 Steps to Find the Problem Statement from Raw Data
##  1. Understand the Business First
  Ask yourself:

What does a coffee shop care about?
(e.g., sales, profits, customer preferences, peak hours, popular items, etc.)

Who are the stakeholders?
(e.g., owner, manager, marketing team)

[Go to Data Cleaning Page](Understand.md)

##   2. Explore the Raw Data
  Look for:

Columns/Fields: e.g., Date, Time, Product, Quantity, Revenue, Customer Type

Patterns: What data is repeated? What seems important?

Missing values: Any gaps or bad-quality data?

Granularity: Daily sales? Transaction level? Customer level?

##  3. Ask Key Questions (Turn into Problem Statements)
Once you understand the data, ask analytical or business-driven questions like:
Possible Question	Can become a Problem Statement
What are the top-selling products?	"Identify which products drive the most sales."
When is the shop busiest?	"Determine peak hours/days to optimize staffing."
Are sales declining in any category?	"Analyze category-wise performance over time."
Do returning customers buy more?	"Evaluate customer loyalty and its impact on revenue."

##  4. Sample Problem Statements for Coffee Shop Data
Here are examples of well-formed problem statements you might derive:

📈 “Analyze daily and monthly sales trends to identify peak revenue periods and potential low-performing days.”

☕ “Identify the most profitable items and their contribution to total revenue.”

🕒 “Determine peak customer hours to optimize staffing and inventory.”

🎯 “Understand customer preferences by analyzing repeat purchase behavior and average spend.”

🧾 “Find operational inefficiencies such as overstocking or unsold products.”

🔧 Example Workflow
Let’s say your raw data has these columns:
Date | Time | Product | Category | Quantity | Price | Total_Amount | Customer_ID
You can:

Use pivot tables to see product-wise totals

Plot time-series charts for daily revenue

Segment customers by frequency of visits

This will guide you to form a relevant problem statement based on what you discover.

✅ Tip:
Write 2–3 hypothetical business goals based on your data → then validate them by doing initial analysis. The most valuable insights will naturally reveal the main problem(s) the coffee shop is facing.

