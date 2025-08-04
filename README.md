# HR Analytics Power BI Dashboard

## 📊 Dashboard Overview

![IPL Dashboard](https://github.com/Kalyanikhapale/HR-Analytics/blob/main/HR-Analytics%20Dashboard.png)

The HR Analytics Dashboard provides insights into key HR metrics, enabling data-driven decision-making. This dashboard helps HR professionals analyze employee demographics, attrition rates, and performance trends efficiently using Power BI.

## 🚀 Key Features

Employee Demographics Analysis: Understand workforce distribution by age, gender, and department.

Attrition Rate Analysis: Identify patterns in employee turnover.

Performance Metrics: Evaluate employee performance across departments.

Salary and Compensation Trends: Analyze salary distributions and trends over time.

Interactive Visuals: Drill-down capability for detailed analysis.

## 📊 Data Cleaning Process

Before building the dashboard, the dataset underwent cleaning to ensure accuracy and consistency:

Removed Unnecessary Columns:

Dropped non-essential columns such as EmployeeCount, StandardHours, EmployeeNumber, and StockOptionLevel as they were not relevant to attrition analysis.

Handled Missing Values:

Identified missing values using the filter dropdown.

Replaced null values in YearsWithCurrManager with the median value.

Filled missing categorical values (e.g., JobRole) with "Unknown".

Used mean/median imputation for missing numerical data.

Removed Duplicates:

Used the "Remove Duplicates" function in Power Query to eliminate redundant records.

Changed Data Types:

Ensured correct data types for each column:

MonthlyIncome, YearsAtCompany → Whole Number or Decimal.

Attrition, JobRole, Department → Text.

OverTime, WorkLifeBalance → Categorical (Text).

## 🛠️ Tools Used

Power BI: Data visualization and dashboard creation.

Power Query: Data cleaning and transformation.

DAX (Data Analysis Expressions): Custom measures and calculated columns.

## 📥 Dataset

The dataset used for this project contains HR-related data, including employee demographics, job roles, salaries, and attrition records.

## 📎 How to Use the Dashboard

Open the HR_Analytics Dashboard.pbix file in Power BI.

Navigate through the various report pages to explore insights.

Use filters and slicers to interact with the data dynamically.

## 🏆 Insights & Findings

Higher attrition rates were observed in certain departments.

Employees with lower performance scores had a higher tendency to leave.

Salary discrepancies were identified across different job roles and genders.

## 📢 Future Enhancements

Implement predictive analytics to forecast attrition.

Integrate external datasets for industry benchmarking.

Improve real-time data connectivity for dynamic updates.

-----
## 👩‍💻 Author

**Kalyani Khapale**
(Data Analysis using PowerBI)
