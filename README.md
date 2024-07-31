# Introduction

In this Project, I created Tableau dashboards according to the specifications of the users, using various csv files as my datasource. The main focus of the dashboard was to visualise Sales and Customer data, in order to identify trends and patterns from the large dataset, ultimately gaining insights into performance and customer preferrances. 

# Background 

The requirements of the Sales and Customer databoard were based on the clients specifications for them, detailed in the user stories below 

<img width="916" alt="Screenshot 2024-07-30 at 4 23 57 PM" src="https://github.com/user-attachments/assets/06f8c28f-62cc-471a-a5f6-4523d7db7ebf">
<img width="913" alt="Screenshot 2024-07-30 at 4 24 11 PM" src="https://github.com/user-attachments/assets/63f3f842-8193-41dd-b3fe-7b424a2c949f">
</br> 

From the user stories above, I decided to break down each requirement individually, getting a better idea of what sort of chart I wanted to use to visualise and present the data with. 

# Sales Dashboard Breakdown

## KPI Overview 

Requirements: Display a summary of total sales, profit and quantity for the current year and the previous year.

### Sales Trends

Requirements: Present data for each KPI on monthly basis for current and previous year. Identify months with highest and lowest sales. 

**KPIs on a monthly basis:** Use multiple-line chart for each KPI to observe change over time (months) and compare current year KPI to previous year. 

**Month with highest and lowest sales:** use colour coded circles to indicate the points in the line chart with the highest and lowerst values. 

**Presenting Multiple KPIs:** Create a banner to fit all the respective KPI charts and include the KPI totals and %change compared to the previous year in the chart's title. Readers can get an idea of the figures and performance of the KPIs in a glance. 

### Product Subcategory Comparison

Requirements: Compare Sales performance by different subcategories for current and previous year, including a comparison of profit and sales. 

**Subcategory Sales Performance:** Multiple-bar chart, altering the size of bar and colours, to compare the current vs previous year sales of product subcategory

**Profit and Sales Comparison:** Accompany bar chart colour coded to signify losses and profits of product categories. 

### Weekly Trends for Sales and Profits 

Requirements: Weekly sales and profit data of current year, display average weekly values and highlight weeks above and below average

**Average Weekly Sales and Profits:** Create 2 step line charts for each KPI, with X-axis being the weeks of the current year. 

**Highlight weeks above and below avg:** Create referrence lines based on the the chart's average value. Indicate using the above colour scheme, values above and below the average. 

### Calculated Fields

**Current Year vs Previous Year:** Calculated fields for current year and previous year are needed in the creation of other calculated field, such as Current/Previous Year (C/PY) Sales/Profits to be displayed on their respective charts. A "Select Year" filter is used to change the year displayed on the chart. 

**Aggregate Functions:** To display Highest and Lowest values, % change values, average Sales/Profit values, etc, aggregate functions need to be used in the calculated fields. 

## Design and Interactivty Requirements 

**Navigation between dashboards:** Create button to navigate between the Customer and Sales dashboards

**Interactive charts and graphs, filter data using charts:** Enable charts to be used as filters, in the dashboard. 

**Check historical data by selecting desired year:** Create Parameter for "Select Year" to input dynamic values for calculation and user interactions. 

**Category, subcategory, region, state, city filters:** Include these filters in the dashboard to control and restrict the visibility of data in all charts. 





