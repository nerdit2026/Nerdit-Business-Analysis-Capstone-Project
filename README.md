# NerdIT Capstone Project
## Superstore Retail Sales Analysis

**Level:** Beginner → Intermediate

**Tools:** Excel, MySQL/SQL, Power BI, Basic Statistics, Generative AI

> Python is NOT required.

## Business Case

You are working as a Junior Business Analyst for a retail company. Management wants a clear view of sales performance, product and category performance, customer contribution, regional performance, and shipping performance.

Your task is to analyze the sales data and present clear business insights and recommendations.

The goal is not complicated analysis. The goal is to answer practical business questions using Excel, SQL, basic statistics, Power BI, and AI.

## Dataset

The project uses `DATA/Sales_project.csv`.

Some fields are already calculated:
- Order Month
- Order Year
- Ship Month
- Ship Year
- Total_Sales_Per_Customer
- Customer_Value
- Delivery_Time

Understand and validate these fields before using them.

## Important Scope

The dataset does not contain:
- Profit
- Discount
- Quantity
- Payment Method
- Customer Review Score
- Seller information
- Expected Delivery Date

Do not make claims about profitability, discount impact, customer satisfaction, seller performance, or late-delivery rate.

# Your Task

## 1. Excel Analysis

Answer:

1. What is the total sales?
2. How do sales change month by month?
3. Which category has the highest sales?
4. What are the top 5 sub-categories by sales?
5. Who are the top 10 customers by sales?
6. Which region has the highest sales?
7. What is the average delivery time?
8. Which shipping mode has the highest number of orders?

Use suitable PivotTables,charts and other tools also.

## 2. SQL Analysis

Load the dataset into MySQL and answer:

1. What are total sales and total orders?
2. What are the monthly sales?
3. Which categories have the highest sales?
4. What are the top 10 products by sales?
5. Which customers have the highest total sales?
6. Which region has the highest sales?
7. How many repeat customers are there?
8. What is the average delivery time for each shipping mode?

Use basic SQL: SELECT, WHERE, GROUP BY, ORDER BY, HAVING and aggregate functions.

## 3. Basic Statistical Analysis

Calculate:

1. Mean Sales
2. Median Sales
3. Minimum Sales
4. Maximum Sales
5. Standard Deviation of Sales
6. Mean Delivery Time
7. Median Delivery Time

Then answer:

- Is mean Sales higher or lower than median Sales?
- What does this tell you about the Sales distribution?
- Which shipping mode has the highest average delivery time?

Perform this task using excel or sql 

## 4. Power BI Dashboard

Create a simple **2-page dashboard**.

### Page 1 — Sales Overview

Include:
- Total Sales
- Total Orders
- Total Customers
- Average Order Value
- Sales by Month
- Sales by Category
- Sales by Region

Add useful slicers such as Year, Region, Category and Segment.

### Page 2 — Customers & Shipping

Include:
- Top 10 Customers
- Sales by Segment
- Orders by Ship Mode
- Average Delivery Time by Ship Mode
- Top 10 Products

Keep the dashboard clean and easy to understand.

## 5. AI in Business Analysis

Use a Generative AI tool.

# AI in Business Analysis — Practice Questions

## 1. Excel 

1. Ask AI to suggest three Excel analyses that can help identify why profit performance differs by region. Perform the suggested analyses in Excel and verify the results.
2. Ask AI to suggest a PivotTable structure for comparing Sales, Cost, Profit and Profit Margin by Region. Create the PivotTable and check whether it answers the business problem.
3. Use AI to explain an Excel formula used to calculate Profit or Profit Margin. Verify the explanation and calculation in Excel.
---

## 2. SQL 

1. Ask AI to generate a SQL query showing total Sales, Cost and Profit by Region. Run the query and verify the results.
2. Write your own SQL query and ask AI to review it for calculation or GROUP BY errors. Check the AI's suggestions by running the query.
3. Ask AI to suggest three business questions that can be answered using SQL from this dataset. Select the relevant questions and write the queries yourself.
---

## 3. Power BI 

1. Ask AI to suggest the most important KPIs for a Power BI dashboard for this business problem. Select and create the relevant KPIs.
2. Ask AI to recommend suitable Power BI visuals for comparing regional Sales, Profit and Profit Margin. Create the visuals and verify that they answer the business question.
3. Give AI the verified dashboard findings and ask it to suggest possible explanations for the lower-performing region. Separate observations from hypotheses and verify the hypotheses using the data.
---

## 4. Statistics 

1. Ask AI which basic statistical measures should be used to compare regional profit performance. Calculate the selected measures and verify the AI's suggestions.
2. Calculate the mean, median and standard deviation of Profit and ask AI to interpret the results from a business perspective. Check whether the interpretation is correct.
3. Ask AI to identify which region appears to have the most consistent profit performance. Verify the answer using the calculated statistics.
---

## AI Prompt Challenge

Write your own prompt using:
**Role + Context + Task + Constraints + Output**
Ask AI to suggest one analysis for this business problem. Perform the analysis using Excel, SQL, Power BI or Statistics and verify whether the AI's suggestion is valid.

## Verification Checkpoint

Before accepting an AI output, verify:

- Is the calculation correct?
- Is the interpretation supported by the data?
- Is the AI making an assumption?
- Can the result be reproduced in Excel, SQL, Power BI or Statistics?


> AI should assist your analysis. You must validate the output.

# Final Business Summary

Prepare a short summary containing:

### Key Findings
Write **3–5 important findings**.

### Recommendations
Give **2–3 practical recommendations** connected to your findings.

### Management Focus
Answer:

> Based on your analysis, what is the most important area management should focus on?

Keep the final summary to approximately **1–2 pages**.

# Required Submission Files

```text
EXCEL_ANALYSIS.xlsx
SQL_ANALYSIS.sql
STATISTICAL_ANALYSIS.xlsx
POWER_BI_DASHBOARD.pbix
AI_IN_BUSINESS_ANALYSIS.md /.xlsx /.sql
FINAL_REPORT.pdf / .ppt
```

# Evaluation

Your project will be evaluated on:
- Correct Excel analysis
- Correct SQL queries
- Basic statistical understanding
- Clear Power BI dashboard
- Responsible use of AI
- Quality of business insights
- Practical recommendations
- Overall clarity

The focus is on **understanding and explaining the business**, not on creating complicated technical solutions.

