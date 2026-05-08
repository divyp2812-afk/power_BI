📊 Sales Data Model – Power BI Project


📌 Project Overview
This project demonstrates data modeling and analysis in Power BI with a focus on:

DAX concepts and calculated logic

Star schema relationships

Matrix‑based reporting (❌ no charts or visuals)

All outputs displayed using Matrix Visual only

🗂️ Dataset Tables
The model uses:

Sales_Fact

Returns_Fact

Customer_Dim

Product_Dim

Date_Dim

Region_Dim

🧮 Calculated Columns
Key calculated fields include:

Profit → Earnings in Sales_Fact

Return Flag → Identifies returned items

Customer Full Name → Combines first + last name

📊 Measures
Business measures created:

Total Sales

Total Cost

Total Profit

Return Rate (%)

Average Sale per Transaction

🎯 Quick Measures
For trend analysis:

YOY Sales Growth

Month‑over‑Month Difference

📦 Measure Management
Dedicated Measure Table created

All DAX measures organized for clarity and structure

🔍 Filter Context & Behavior
Matrix visual used to explore:

Sales comparison with vs. without filters

Filter logic to control visibility and aggregation

⚙️ DAX Functions & Concepts
Applied core DAX techniques:

Aggregations → SUM, AVERAGE, MAX

Logical → IF, SWITCH

Text → CONCATENATE, FORMAT

Date → YEAR, MONTH, EOMONTH

🔗 Relationships
Star schema design

Fact ↔ Dimension relationships

Enables cross‑table analysis

⏳ Time Intelligence
Time‑based calculations:

YTD Sales & Returns

Previous Year Comparison

Running Totals

Used for:

Monthly performance tracking

Yearly comparison

Trend analysis

🧠 Advanced Scenarios
Categorization: Sales → Low / Medium / High

Iterative calculations for deeper insights

<img width="1915" height="974" alt="image" src="https://github.com/user-attachments/assets/e0300e65-c3a6-423f-baa9-d199a5c5db59" />
<img width="1919" height="1012" alt="image" src="https://github.com/user-attachments/assets/06daf6d3-50cd-4dc0-b4cf-87c2969e5484" />
<img width="1919" height="975" alt="image" src="https://github.com/user-attachments/assets/43dffee9-b997-4fba-aa94-dbb34603115c" />
<img width="1912" height="1006" alt="image" src="https://github.com/user-attachments/assets/858cf598-e912-4702-a673-0afeb8c45a16" />
<img width="1919" height="1004" alt="image" src="https://github.com/user-attachments/assets/2ff51cb4-827a-4c96-851a-2d821602af2e" />
