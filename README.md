# Plant Sales Performance Dashboard

### Dashboard Link:https://app.powerbi.com/links/hnGgnOfIb9?ctid=1f436841-fd31-4aac-b492-9d1b692c157b&pbi_source=linkShare&bookmarkGuid=9f9c3270-6838-4e58-99c5-b5c18235ab7d

## Problem Statement
This Power BI dashboard provides comprehensive insights into the Plant Sales Performance for the year 2023. The primary objective of this report is to evaluate the company's sales performance across various regions, product types, and time periods. The dashboard helps in understanding Plant Sales, Quantity Sold, and Gross Profit over the years while comparing Year-on-Year (YoY) performance to uncover trends, areas of improvement, and sales distribution patterns. The analysis highlights key sales trends, underperforming regions, and actionable insights to enable data-driven decision-making

## Steps Followed

### Data Preparation
- **Step 1:** Data was loaded into Power BI from multiple data sources, including sales transactions and product information.
- **Step 2:** Data cleaning and transformation were performed using **Power Query** to remove null values, correct data types, and format columns.
- **Step 3:** New calculated columns were created using **DAX** to derive:
  - YTD Sales
  - PYTD Sales
  - YTD vs PYTD Difference
  - Gross Profit Percentage (**GP%**)

### Visualizations and Design
- **Step 4:** A consistent **Storm theme** was applied to ensure uniform styling across the dashboard.
- **Step 5:**  slicers added to filter data
 
  - Type of Values : Sales, Quantity, and Gross Profit
  - Year : Slicer to filter data by different years.
  - Product Type, Quarter, Month, and Country to filter data based on product type and time periods.

     ![Image](https://github.com/user-attachments/assets/67b445dd-a055-40f3-bb54-b5355fcc37bd)
     ![Image](https://github.com/user-attachments/assets/f36a1b49-44bf-4842-8715-60293121dbe2)
   
   

- **Step 6:** KPI cards were used to display:
  - YTD Sales
  - PYTD Sales
  - YTD vs PYTD Difference
  - Gross Profit Percentage (**GP%**)
     ![Image](https://github.com/user-attachments/assets/6c660d46-8fd2-495c-ae46-d5491dc4be88)

- **Step 7:** Line charts and graphs were created to visualize:
 
     - waterfall chart is used to track YTD vs PYTD diffrence with drill down options for Quarterly data | Monthly Data | Acroos Countries | Across Product to track the contributers to diffrence

        ![Image](https://github.com/user-attachments/assets/c2c117bd-2655-435f-a8c9-761bd66d6dea)
     - Monthly Sales | Quantity | Gross Profit Performance
     - Quarterly Sales  | Quantity | Gross Profit Performance
     - Bottom 10 Countries by Sales Difference to focus on improvement
     - A Line and Stacked Column Chart was used to visualize YTD vs PYTD values along with YTD contributors by product type

       ![Image](https://github.com/user-attachments/assets/537468a0-6f15-4669-af3c-9bc953ec93e2)
     - Gross Profit % VS Sales | Quantity | Gross Profit spread  by Account ID with the help of Scatter plot with Average lines to get clear picture

- **Step 8:** The report was optimized for interactivity, allowing users to drill down into sales performance by product, country, and month.
- **Step 9:** All the titles are formated according to slciers used with the help of title measures.

- **Step 10:** The report was published to **Power BI Service** for sharing with stakeholders.

## Insights

### [1] Overall Sales Performance
- **YTD Sales:** 13.00M
- **PYTD Sales:** 13.51M
- **YTD vs PYTD Difference:** -512.26K
- **Gross Profit Percentage:** 39.62%

The report indicates a **3.8% decline in 2023 YTD Sales** compared to the previous year 2022, which highlights the need for further investigation into declining regions and product categories.

### [2] Bottom 10 Countries by YTD vs PYTD Sales for 2023
- **China:** -760.40K
- **Sweden:** -240.09K
- **France:** -149.78K
- **Norway:** -118.66K
- **Poland:** -112.00K
- **Netherlands:** -96.72K
- **United States:** -76.69K
- **Greece:** -61.97K
- **Thailand:** -55.73K
- **Pakistan:** -46.85K

These countries represent the largest contributors to the overall decline in sales. **China** had the highest negative impact, accounting for more than **1.4x** the decline of the second-highest country.

### [3] Quarterly Performance
| Quarter  | YTD vs PYTD Difference |
|----------|-----------------------|
| Q1       | -0.36M              |
| Q2       | +0.50M             |
| Q3       | -0.25M             |
| Q4       | -0.40M             |
| **Total** | **-0.51M**        |

While **Q2** experienced a positive growth of **0.50M**, all other quarters experienced a decline, contributing to the overall negative sales trend.

### [4] Monthly Sales Performance
| Month     | YTD Sales | PYTD Sales | Difference |
|----------|----------|----------|-----------|
| January  | 1.07M   | 1.13M   | -0.06M   |
| February | 0.81M   | 0.94M   | -0.13M   |
| March    | 1.19M   | 1.19M   | 0.00M    |
| April    | 1.34M   | 1.14M   | +0.20M   |
| May      | 1.17M   | 1.15M   | +0.02M   |
| June     | 0.98M   | 1.10M   | -0.12M   |
| July     | 0.94M   | 1.13M   | -0.19M   |
| August   | 1.19M   | 1.14M   | +0.05M   |
| September| 1.19M   | 1.15M   | +0.04M   |
| October  | 1.13M   | 1.10M   | +0.03M   |
| November | 1.38M   | 1.13M   | +0.25M   |
| December | 0.94M   | 0.94M   | 0.00M    |

## Suggestions for Improvement
- Prioritize **China, Sweden, and France** for sales recovery strategies.
- Launch **targeted marketing campaigns** during peak months for Indoor and Outdoor products.
- Introduce **promotional offers** in Q1 and Q3 to counter seasonal dips.
- Optimize **inventory management** based on quarterly demand patterns.
- Leverage **predictive analytics** to anticipate demand and adjust supply chain operations.

### Report Snapshots
 ![Image](https://github.com/user-attachments/assets/bef9dd9a-381f-49ad-a3d1-c7584c2f83fc)

---

This Power BI dashboard serves as a comprehensive tool for understanding Plant Co.'s sales performance and identifying actionable insights for business growth.

# Projects
