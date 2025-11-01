# Sales-Analysis-Online-Retail

## Project Description
Sales data analysis project using Python and Excel to extract business insights from online retail data.Exploring sales patterns, top-selling products, and seasonal trends in an online retail dataset.
## Dataset
The dataset contains transactional data from an online retail store, including:
- InvoiceNo: Transaction ID
- StockCode: Product ID
- Description: Product name
- Quantity: Number of units sold
- InvoiceDate: Date of transaction
- UnitPrice: Price per unit
- CustomerID: Unique customer identifier
- Country: Customer location

Source: [Online Retail Dataset on Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset)

## Tools & Technologies
- Python (pandas, numpy, matplotlib, seaborn)
- Excel (optional)
- Jupyter Notebook

## Steps / Methodology
1. Data Cleaning: Removed missing values and duplicates, handled negative quantities.  
2. Data Exploration: Examined top products, countries, and monthly revenue trends.  
3. Analysis:
   - Monthly sales trends
   - Top-selling products
   - Revenue by country
4. Visualization: Generated charts to highlight insights and patterns.

## Key Insights / Findings
# 1. Monthly Revenue Over Time
Description: A time-series line plot showing total monthly revenue across the dataset.
Insight:
Clear upward trend from mid-year onward, with a sharp rise toward the holiday season (October–November).
The drop in December could be due to data cut-off or post-holiday slowdown.
Confirms seasonal growth cycles and supports planning for peak demand periods.
# 2. Quantity vs. Revenue
Description: A scatter plot showing the relationship between the number of items sold (Quantity) and the total sales (Revenue).
Insight:
Most transactions involve small quantities and low revenue, clustered near the origin.
A few outliers represent bulk or high-value orders that generate disproportionately higher revenue.
Indicates a highly skewed sales distribution, where a small number of transactions drive large portions of revenue.
# 3. Seasonal Sales Trend
Description: A line plot of average monthly revenue across the year to reveal seasonality.
Insight:
Sales start relatively low early in the year and increase steadily toward the last quarter.
Peaks around October–November, suggesting strong seasonal demand, possibly due to holidays or year-end promotions.
Seasonal patterns can guide inventory and marketing strategies.
# 4.Top 10 Countries by Revenue
Description: A bar chart ranking the top countries by total revenue.
Insight:
The United Kingdom dominates sales by a huge margin, far exceeding other countries.
Other top contributors include the Netherlands, EIRE (Ireland), Germany, and France.
Suggests the business is heavily UK-centric, with international expansion potential.
# 5. Top 10 Customers by Revenue
Description: A horizontal bar chart of the top customers ranked by total spending.
Insight:
The top few customers contribute disproportionately high revenue, creating a customer concentration risk.
Retaining these high-value customers is critical for revenue stability.
Can inform VIP loyalty programs or personalized offers for these key accounts.
# 6.Top 10 Products by Revenue
Description: A bar chart ranking the top-selling products by total revenue.
Insight:
“PAPER CRAFT, LITTLE BIRDIE” and “REGENCY CAKESTAND 3 TIER” are the best performers.
Top products show a mix of decorative and functional items, indicating strong demand for giftable home goods.
Understanding these can help focus marketing and inventory on proven revenue drivers.
## Folder Structure

Sales_Analysis/
├── Data/           # Raw dataset (online_retail.csv)
├── Notebooks/      # Python notebooks
├── Visualizations/ # Charts and plots
└── README.md



## How to Run
1. Clone the repository:
2. Open `sales_analysis.ipynb` in Jupyter Notebook.
3. Run the cells to see the analysis and visualizations.

