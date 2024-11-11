# CODETECH - TASK 2
NAME - ADITI SONI
COMPANY - CODETECH IT SOLUTIONS
ID - CT08DS8707
DOMAIN - POWER BI 
DURATION- 1 MONTH


Project Overview
The Customer Demographics Analysis dashboard provides a comprehensive view of customer data, including age, gender, income, and geographic location. The purpose is to help businesses make data-driven decisions to tailor marketing strategies, target customer segments more effectively, and improve overall customer engagement.
SNAPSHOT - 
![TASK 2](https://github.com/user-attachments/assets/e743bc01-b0de-4654-82d9-fcd0ae91b3bf)


Problem Statement
This analysis focuses on understanding the characteristics of a company's customer base through demographic data. By exploring factors such as age, gender distribution, income levels, and regional concentration, the dashboard enables data-backed decisions to optimize marketing, identify high-value customer segments, and guide strategic business improvements.

Data Insights
Total Customers: 1,000
Average Age: 35 years
Average Income: $56,000
Gender Ratio: 52% Male, 48% Female
Key Insights
Age Distribution: Analyze the spread of customer ages to understand which age groups engage the most.
Income Levels: View income distribution to gauge customer purchasing power.
Geographic Concentration: Identify areas with higher customer density to adjust regional strategies.
Spending Behavior: Segment customers based on demographics to align with spending patterns and preferences.
Steps to Create the Dashboard
1. Data Import
Loaded the CSV file containing customer demographics into Power BI Desktop.
2. Data Profiling
Enabled Column Distribution, Column Quality, and Column Profile in Power Query Editor to review data quality and consistency.
3. Data Cleaning
Addressed missing values, standardized formats, and ensured accuracy for analysis.
4. Visual and Theme Selection
Applied a custom theme for a consistent visual style across dashboard elements.
5. Key Performance Indicators (KPIs)
Created card visuals to highlight essential metrics:
Total Customers
Average Age
Average Income
Gender Ratio (Male to Female)
6. Slicers for Interactive Filtering
Added slicers for Age Group, Gender, Location, and Income Range to allow detailed analysis by specific customer attributes.
7. Visualizations
Age Distribution: Bar chart showing age distribution.
Gender Breakdown: Pie chart for gender ratio.
Geographic Map: Heatmap showing customer density by region.
Income Levels: Stacked bar chart for income across demographics.
Spending Segments: Donut and column charts for segmentation based on demographic characteristics.

8. Calculated Columns and Measures
Added custom DAX measures for insights, such as:
Average Income = AVERAGE(Customers[Income])
9. Publishing
Published the dashboard to Power BI Service for easy access and sharing.
Gender Ratio Calculation:
Gender Ratio = DIVIDE(CALCULATE(COUNT(Customers[Gender]), Customers[Gender] = "Male"), COUNT(Customers[Gender]))

Repository Structure
customer-demographics-analysis/
├── data/
│   └── customer_demographics.csv               # Customer demographics dataset
├── dashboard/
│   └── customer_demographics_dashboard.pbix    # Power BI Dashboard file
├── README.md                                   # Documentation
└── images/
    ├── customer_demographics_snapshot.jpg      # Dashboard Snapshots
    ├── gender_ratio_snap.jpg                   # Gender Ratio Calculation Snap
    └── report_snapshot.jpg                     # Additional Report Snapshots

Future Enhancements
Enhanced Segmentation: Drill-down capabilities based on more specific attributes such as lifestyle, purchasing habits, or loyalty status.
Predictive Analysis: Incorporate predictive models to identify potential high-value customers based on their demographics.
Interactive Visualizations: Add additional interactive visuals to allow real-time analysis of various demographics.
License
This project is licensed under the MIT License.

