# Introduction

In this Project, I created Tableau dashboards according to the specifications of the users, using various csv files as my datasource. The main focus of the dashboard was to visualise Sales and Customer data, in order to identify trends and patterns from the large dataset, ultimately gaining insights into performance and customer preferrances. 

# Background 

The requirements of the Sales and Customer databoard were based on the clients specifications for them, detailed in the user stories below 

<div align = "center">
  
<img width="916" alt="Screenshot 2024-07-30 at 4 23 57 PM" src="https://github.com/user-attachments/assets/06f8c28f-62cc-471a-a5f6-4523d7db7ebf">
<img width="913" alt="Screenshot 2024-07-30 at 4 24 11 PM" src="https://github.com/user-attachments/assets/63f3f842-8193-41dd-b3fe-7b424a2c949f">

</div>

</br> 

From the user stories above, I decided to break down each requirement individually, getting a better idea of what sort of chart I wanted to use to visualise and present the data with. 

# Sales Dashboard Breakdown

## KPI Overview 
Display a summary of total sales, profit and quantity for the current year and the previous year.

### Sales Trends
Requirements: Present data for each KPI on monthly basis for current and previous year. Identify months with highest and lowest sales. 

**KPIs on a monthly basis:** Use multiple-line chart for each KPI to observe change over time (months) and compare current year KPI to previous year. 

**Month with highest and lowest sales:** use colour coded circles to indicate the points in the line chart with the highest and lowerst values. 

**Presenting Multiple KPIs:** Create a banner to fit all the respective KPI charts and include the KPI totals and %change compared to the previous year in the chart's title. Readers can get an idea of the figures and performance of the KPIs in a glance. 

</br>
<div align = "center" >
  <img width="600" alt="Screenshot 2024-07-31 at 1 43 52 PM" src="https://github.com/user-attachments/assets/2b48071b-d291-45f0-907c-b477dfa09678">
</div>
</br>

### Product Subcategory Comparison
Requirements: Compare Sales performance by different subcategories for current and previous year, including a comparison of profit and sales. 

**Subcategory Sales Performance:** Multiple-bar chart, altering the size of bar and colours, to compare the current vs previous year sales of product subcategory

**Profit and Sales Comparison:** Accompany bar chart colour coded to signify losses and profits of product categories. 

</br>
<div align = "center" >
  <img width="870" alt="Screenshot 2024-07-31 at 1 44 08 PM" src="https://github.com/user-attachments/assets/008689e5-4b26-43f4-945d-5397473c1f47">
</div>
</br>

### Weekly Trends for Sales and Profits 
Requirements: Weekly sales and profit data of current year, display average weekly values and highlight weeks above and below average

**Average Weekly Sales and Profits:** Create 2 step line charts for each KPI, with X-axis being the weeks of the current year. 

**Highlight weeks above and below avg:** Create referrence lines based on the the chart's average value. Indicate using the above colour scheme, values above and below the average. 

</br>
<div align = "center" >
  <img width="891" alt="Screenshot 2024-07-31 at 1 44 30 PM" src="https://github.com/user-attachments/assets/6a9df462-e06d-40b1-9a69-47a6d8eac33a">
</div>
</br>

# Cuatomer Dashboard

## KPI Overview 
Summary of total customers, total sales per customer & total number of orders for current and previous year. 

### Customer Trends
Requirements: Present data for each KPI on monthly basis for current and previous year, identify highest and lowest values. 

**Presenting Multiple KPIs:** Same format as the Sales Trends, change to the corresponding KPI. 

</br>
<div align = "center" >
  <img width="890" alt="Screenshot 2024-07-31 at 8 02 24 PM" src="https://github.com/user-attachments/assets/451af7c5-6466-4eba-8a44-8296f5dc435c">
</div>
</br>

### Customer distribution by Number od Orders
Requirements: Distribution of Customers based on number of orders, provide insights on customer behaviour, loyalty and enagagement. 

**Customer distribution by number of orders:** Use a histrogram to display the distribution. 

</br>
<div align = "center" >
  <img width="500" alt="Screenshot 2024-07-31 at 8 02 39 PM" src="https://github.com/user-attachments/assets/3df29792-8781-4b93-b1b6-134647288016">
</div>
</br>

### Top 10 Customers by Profit
Requirements: Present top 10 customers based on profit generated, with additional info like rank, current sales, current profit and last order. 

**Top 10 Customer Insights:** Create a table with the rows as customer names and the columns as the info required 

</br>
<div align = "center" >
  <img width="460" alt="Screenshot 2024-07-31 at 8 02 58 PM" src="https://github.com/user-attachments/assets/834ea6e7-e090-49c7-936c-6e5e81347d68">
</div>
</br>

### Calculated Fields

**Current Year vs Previous Year:** Calculated fields for current year and previous year are needed in the creation of other calculated field, such as Current/Previous Year (C/PY) Sales/Profits to be displayed on their respective charts. A "Select Year" filter is used to change the year displayed on the chart. 

**Aggregate Functions:** To display Highest and Lowest values, % change values, average Sales/Profit values, etc, aggregate functions need to be used in the calculated fields. 

# Final Dashboard Design 

This is the final Sales and Customer Dashboard design. The top most banner includes the Company Logo, Dashboard Name, current Year it displays and 3 Buttons that allow for navigation and showing and hiding for filters.
The second banner below it consists of the charts of the requested KPIs, and a legend indicating what the colours correspond to. 
The last banner below it includes 2 charts, displaying the specified information from the requirements.

</br>
<div align = "center" >
  <img width="900" alt="Screenshot 2024-07-31 at 8 16 27 PM" src="https://github.com/user-attachments/assets/9d234090-4521-4d30-a48c-89d6890f40b8">
</div>
</br>


## Design and Interactivty Requirements 

**Navigation between dashboards:** Create button to navigate between the Customer and Sales dashboards

</br>
<div align = "center" >
  <img width="210" alt="Screenshot 2024-08-01 at 10 35 37 AM" src="https://github.com/user-attachments/assets/1235946d-da73-484d-8441-dc6ce90e679a">
  <img width="210" alt="Screenshot 2024-08-01 at 10 41 36 AM" src="https://github.com/user-attachments/assets/ec9db3e6-f7d4-4d85-a630-32d30fc3912f">
</div>
</br>
Clicking on the buttons with icons representing the 2 different dashboards and navigates to them respectively. The icon shaded white indicates which dashboard is currently on view. 

## **Interactive charts and graphs, filter data using charts:** Enable charts to be used as filters, in the dashboard.

</br>
<div align = "center" >
  <img width="900" alt="Screenshot 2024-08-01 at 10 39 57 AM" src="https://github.com/user-attachments/assets/1b0dbcb7-5efe-4798-8b1f-a8d6d48598ae">
</div>
</br>
Users can click on a chart element, such as a bar in a bar chart or a point in a line plot, to filter the entire dashboard based on that selection. This interactivity allows users to explore the data dynamically and uncover insights that might not be apparent from static views. Users can also quickly access and analyze relevant data without having to manually set multiple filters. This efficiency is particularly beneficial in real-time data analysis scenarios where timely insights are critical.

</br>
## **Check historical data by selecting desired year:** Create Parameter for "Select Year" to input dynamic values for calculation and user interactions. 

## **Category, subcategory, region, state, city filters:** Include these filters in the dashboard to control and restrict the visibility of data in all charts. 
</br>
<div align = "center" >
<img width="205" alt="Screenshot 2024-08-01 at 10 32 08 AM" src="https://github.com/user-attachments/assets/94198f2c-afd7-4958-83e2-a52c88521ee3">
<img width="900" alt="Screenshot 2024-08-01 at 10 31 58 AM" src="https://github.com/user-attachments/assets/3af07ad9-6b78-4baf-9ec8-8a5a485b048d">
</div>
</br>

The drop down filter buttton displays the fields readers can filter the data from. Its user-friendly interface is easy and intiutive to use, with a simple and clean panel design that is unobstrusive. Applying filters updates the dashboard visuals in real-time, providing instant feedback and insights. Users can also combine multiple filters to create custom views, tailoring the data to their specific needs and questions.


