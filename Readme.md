                       
                        Superstore Sales Analysis

An end-to-end analysis of a retail superstore's orders (2014 to 2017)
using Python (Pandas, Matplotlib), SQL (SQLite), and Excel.

Tools Used :
Python, Pandas, Matplotlib, SQL (SQLite), Jupyter Notebook, Excel

Files :
Sample - Superstore.csv`: raw data
superstore_clean.csv`: cleaned data
notebooks/`: step-by-step Jupyter notebooks
charts/`: exported charts

Dataset :
Superstore sales data from Kaggle: 9,994 rows and 21 columns
(9,993 rows after cleaning). Each row is one product line in an order.
Total sales: [ 2,296,919]. Total profit: [286,409].

Process :
1. Explore: reviewed columns, data types, and summary statistics.
2. Clean: checked missing values (none), removed 1 hidden duplicate,
   converted dates, fixed postal codes, created 6 new columns.
3. Analyze with SQL: answered the 5 questions using GROUP BY,
   aggregate functions, and a subquery.
4. Visualize: built 4 charts with Matplotlib.

Key Findings :
1) Region: West earns the most profit (108,418) and Central the least
   (39,706). Central has higher sales than South but lower profit.
2) Discounts: average profit is positive up to a 20% discount and turns
   negative from 30%. The worst level is 50%, with an average loss of about 310 per row.
3) Sub-categories: [your loss-making sub-categories] lose money overall.
4) Trend: orders grew from 1,992 in 2014 to 3,312 in 2017, with sales
   peaks in [your peak months].

Recommendations: 
- Limit discounts above 20%.
- Review pricing on [loss-making sub-categories].
- Plan stock and staff for the end-of-year sales peak.


Charts :
1) [Profit by Region](charts/1_profit_by_region.png)
2) [Profit by Sub-Category](charts/2_profit_by_subcategory.png)
3) [Discount vs Profit](charts/3_discount_vs_profit.png)
4) [Monthly Trend](charts/4_monthly_trend.png)

