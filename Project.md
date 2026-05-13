AdventureWorks Project

- [View Dashboard](https://github.com/Ayushipundir-cloud/Excel-Projects-Hub/blob/main/Dashboard.png)

AdventureWorks is a Microsoft sample database representing a fictional global bicycle manufacturing and sales company. It is one of the most widely used datasets in the data analytics and business intelligence community for hands-on learning and portfolio.

## 📊 Dataset Structure — Star Schema

| Table | Type | Description |
|---|---|---|
| **Union** (FactInternetSales) | Fact | Core transactional data — sales revenue, order quantity, profit, cost |
| **DimCustomer** | Dimension | Customer profiles, demographics, income level, education |
| **DimProduct** | Dimension | Product names, SKUs, standard cost, list price |
| **DimProductCategory** | Dimension | High-level product categories (Bikes, Accessories, Clothing) |
| **DimProductSubCategory** | Dimension | Sub-level product groupings under each category |
| **DimDate** | Dimension | Full date hierarchy — day, month, quarter, year, fiscal year |
| **DimSalesTerritory** | Dimension | Regional groupings — country, region, and sales zone |

## 📈 Key Business Metrics Analyzed

| Metric | Description |
|---|---|
| **Total Sales Revenue** | Overall internet sales performance across time periods |
| **Total Profit** | Revenue minus product cost for margin analysis |
| **Sales vs Budget** | Actual performance benchmarked against sales targets |
| **Order Quantity** | Volume of transactions across products and regions |
| **Top Performing Products** | Identifying best-selling SKUs by revenue and quantity |
| **Customer Segmentation** | Analysis by age group, income level, and geography |
| **Regional Contributions** | Country-wise and territory-wise revenue breakdown |
| **Year-over-Year Trends** | Multi-year sales trends and seasonal patterns |

🔍 Key Business Insights from the Dataset

Bikes are the dominant product category, contributing the majority of total revenue
The dataset supports demographic segmentation — enabling profit analysis by age group and customer profile
Geographic data allows regional performance comparisons across countries and territories
Sales trends reveal clear seasonality patterns useful for forecasting
The Budget table enables variance analysis — comparing planned vs actual sales performance


🛠️ Tools & Techniques Applied
Tool / TechniquePurposePower QueryData import, cleaning, transformation, and shapingPower PivotData modeling and building relationships between tablesPivot TablesSummarizing and aggregating data dynamicallyDAX MeasuresCustom KPIs, calculated columns, and business metricsCharts & VisualsBar, line, map, and pie charts for insight communicationExcel MacrosAutomating repetitive reporting tasksConditional FormattingHighlighting KPI performance thresholds

✅ Skills Demonstrated

ETL (Extract, Transform, Load) process using Power Query
Data modeling with Star Schema relationships
Building interactive and dynamic Excel dashboards
KPI tracking and Sales vs Budget variance analysis
Customer behavior and geographic contribution analysis
Product performance and profitability reporting
Time-series analysis and year-over-year comparisons

<img width="915" height="393" alt="Dashboard" src="https://github.com/user-attachments/assets/43b39235-b092-4fc6-97d9-200c624050d4" />


