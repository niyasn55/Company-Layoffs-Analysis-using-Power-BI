# Company-Layoffs-Analysis-using-Power-BI
📁 Project Description
This project analyzes global company layoffs data using Power BI. The dataset includes information on layoffs, industries, companies, years, and funds raised. The aim is to visualize trends, identify top affected sectors, and derive insights to understand the impact of layoffs.

🗂️ Dataset
File Name: employee_cleaned.xlsx

Source: Cleaned version of the raw layoffs dataset

Columns Included:

Company Name

Industry

Percentage Laid Off

Total Laid Off

Date

Location

Funds Raised

📈 Visualizations in Power BI
Bar Chart: Top companies by total layoffs

Donut Chart: Top 10 industries by layoff percentage

 Area Chart: Layoffs trend over the years

Map Chart: Layoffs by geographic location

Table: Monthly and yearly breakdown of layoffs

KPI Cards: Summary of total layoffs, funding, and company count

Slicers: Year-wise interactive filter for dynamic views

🧠 DAX Measures Used
Total Layoffs = SUM('Table'[Total_Laid_Off])

Selected Year = SELECTEDVALUE('Date'[Year])

🖥️ Requirements
Microsoft Power BI Desktop

Basic knowledge of DAX (Data Analysis Expressions)

📌 How to Use
Clone or download this repository

Open the Power BI file Layoffs_Visualization.pbix

Load the employee_cleaned.xlsx file

Explore the visuals and interact using slicers

✅ Insights Derived
Highest layoffs occurred in the Tech Industry

📉 Most layoffs were recorded in 2022, peaking at 230K.

🏢 Top companies with highest layoffs include Amazon, Google, Meta.

🏭 Highest impacted industries include Tech, Finance, and Consumer.

💰 Netflix raised the highest fund among affected companies.

2022 saw a significant spike in layoffs

Companies like Amazon, Google, and Meta were the top contributors

Total layoffs: 493K, Total fund raised: 2M USD

📬 Author
Name: NIYAS N
