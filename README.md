# Retail-Sales-Intelligence-Project-for-Data-Analytics-Business-Insights
A  retail sales analytics project involving data cleaning, exploratory data analysis, visualization, and storytelling. Covers sales trends, regional performance, product profitability, and seasonal behavior. The project integrates MySQL data extraction, Python analysis, and a professional report summarizing insights and strategy recommendations.

📌 Project Overview
This project showcases my complete end-to-end data analytics process using a real-world sales dataset. I worked through every stage manually — beginning from the raw, unprocessed data and ending with a fully interactive analytics dashboard.

My goal was not only to analyze the sales data but also to **demonstrate a full professional workflow** including:

* Data acquisition
* Data quality checks
* Data cleaning
* Data transformation & feature engineering
* Exploratory Data Analysis (EDA)
* Business insight generation
* Dashboard creation
* Documentation

This folder contains the dataset exactly as I received it:
✔ Uncleaned
✔ Unmodified
✔ Full of missing values, inconsistencies, dtype issues, etc.

I kept the raw version untouched to ensure reproducibility.

After performing all cleaning tasks — fixing missing values, duplicates, wrong categories, date formatting, and more — the cleaned version is saved.

This folder includes the enhanced version of the dataset after feature engineering (additional metrics such as total_sales, month, etc.)

A carefully structured set of notebooks:

→ Shows the entire cleaning process step-by-step
→ Contains graphs, summary statistics, trend analysis, etc.
→ Final calculations, pivot tables, segmentation, insights

Contains executive-level artifacts:

– My interactive Power BI dashboard
– A business report summarizing findings

1️⃣ Raw Data Description (Highly Descriptive)

The raw dataset included common real-world inconsistencies. Here is what I observed:

✔ Multiple Data Types Mixed Together

For example, dates stored as text, numbers saved as strings, or inconsistent column naming. These issues make calculations inaccurate.

✔ Missing Values

Several rows had missing:

* Prices
* Customer types
* Branch names
* Invoice IDs

These missing values can distort revenue totals and customer segmentation.

✔ Duplicates

Some transactions appeared more than once — a major problem in business analysis because duplicates inflate totals.

✔ Outliers

Very high or very low quantities or prices — possibly due to errors or exceptional events.

✔ Column Naming Issues

Some columns had long names, spaces, uppercase–lowercase inconsistencies making them easy to mistype in analysis.

Documenting the raw data helped me plan the next steps.

2️⃣ Data Cleaning (Fully Described)

✔ 1. Missing Values

I analyzed all missing entries and used appropriate strategies:

This ensured all rows were complete and usable.

✔ 2. Duplicate Removal

I removed all exact duplicate transactions to avoid inflated revenue totals.

This step was crucial because:

* Duplicates cause false increases in total sales
* Dashboard KPIs become unreliable
* Monthly analysis becomes misleading

✔ 3. Standardizing Date Formats

Dates appeared in multiple inconsistent formats.
I converted everything into a proper `datetime` data type and extracted meaningful time-based features like:

* Month

These features are essential for time-series analysis.

✔ 4. Cleaning Categorical Fields

I standardized values like:

* payment method
* product category
* customer type
* branches

This improved grouping and visualization.

✔ 5. Handling Outliers

I inspected abnormally high or low values and checked if they were:

* **Data entry errors** → removed
* **Unusual but valid events** → kept and flagged

This prevents misleading averages.

✔ 6. Renaming Columns

Finally, I made all columns:

* short
* descriptive
* analysis-friendly

Example:
`Unit Price (USD)` → `unit_price`

All cleaned data was saved 

3️⃣ Data Transformation & Feature Engineering (Highly Descriptive)

After cleaning, I transformed the dataset to make it more useful for analysis.

✔ 1. Creating New Calculated Fields

I created important metrics such as:

* **total_sales = unit_price × quantity**
* **profit margin (if cost available)**
* **sales_category (low, medium, high)**

These fields help reveal deeper insights.

✔ 2. Time-Based Breakdown**

I extracted:

* month name

This allowed me to analyze seasonal trends and cycle patterns.

3. Customer Segmentation

Using customer_type and payment_method, I grouped buyers into categories such as:

* Regular customers
* Members
* High-value customers
* Cash vs Card buyers

4. Branch & Region Tagging

I categorized each branch into:

* High-performing
* Average
* Low-performing

based on revenue thresholds.

B. Trend Analysis

I explored:

* Monthly revenue trends
* Seasonal peaks
* Slow sales periods
* Weekday vs Weekend performance

C. Product Analysis

I identified:

* Best-selling products
* Worst-performing products
* Products with high profit margins
* Products that contribute the highest revenue

✔ D. Customer Analysis

I compared customer types based on:

* Average spending
* Preferred payment method
* Purchase frequency

✔ E. Regional/Branch Analysis

I discovered:

* Which branch performs best
* Which needs improvement
* Regional sales differences

5️⃣ Business Insights (Descriptive & Practical)

Here are some examples of the insights I generated:

1. Top Products Drive Majority of Revenue

A small subset of products consistently generated the highest revenue — useful for targeted marketing.

2. Some Branches Consistently Outperform Others

Top branches indicated strong customer reach and good location strategy.

3. Clear Seasonal Patterns

Certain months showed predictable sales peaks — important for forecasting.

4. Customer Segmentation Opportunities

Member customers spent more on average than walk-ins.

5. Payment Method Optimization

Card/POS payments were used more frequently, suggesting the need to maintain fast electronic systems.

All insights were documented in the PDF report.

6️⃣ Dashboard (Explained in Detail)

My Excel dashboard includes:

✔ Revenue KPIs

* Total sales
* Average sales
* Number of transactions

✔ Product Visuals

* Top 10 products
* Revenue by category

✔ Regional Analysis

* Sales by branch
* Branch ranking

✔ Customer Behavior

* Spending by customer type
* Payment method distribution

✔ Time-Series Graphs

* Monthly sales trend
  
All visuals include filters for fully interactive analysis.

7️⃣ Conclusion (Personalized & Strong)

This project allowed me to demonstrate my ability to work through the **full data analytics lifecycle** on my own — from raw data to executive insights.

I successfully showed skills in:

* Data cleaning
* Data transformation
* Exploratory data analysis
* Business insight generation
* Dashboard development
* Professional documentation

This project reflects my competence as a data analyst capable of delivering clean, accurate, actionable, and business-ready results.

8️⃣ Tools I Used (Explained)**

⚙ Python (Pandas, NumPy, Matplotlib, Seaborn)

For cleaning, transformations, and visual EDA.

⚙ Excel

For initial validation and cross-checking data types.

⚙ Excel

For dashboard creation and KPI reporting.

For documenting step-by-step processes.


8. Explore filters, visual KPIs, and insights
9. Read the summary PDF for business conclusions
