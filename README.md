# Attendance Analysis Dashboard

This project is part of the Data Analysis Projects series by Codebasics. It focuses on analyzing HR data to uncover insights related to employee attrition, performance, and other HR metrics. The project demonstrates data cleaning, exploratory data analysis (EDA), and visualization using Python.

## Objectives

1. Analyze working preferences of employees (office vs. work from home).
2. Determine the percentage of sick leave taken by employees each month.

## Features

### Data Preparation (Power Query)

1. Imported the raw attendance data.
2. Created a template to use as a parameter for a function.
3. Developed a custom function to concatenate data from three sheets.
4. Combined the three sheets into one query for streamlined analysis.

### Data Transformation

- Added custom columns for analysis:
  - **Work From Home Count**
  - **Sick Leave Count**
  - **Week No || Day || Month**

### DAX Measures

Created key performance measures to support the analysis:
- **Presence Percentage**
- **Present Days**
- **Sick Leave Percentage**
- **Total Working Days**
- **Work From Home Percentage**

### Dashboard Highlights

The interactive dashboard visualizes attendance trends and provides key insights:
- **Presence % by Day**: Tracks daily presence trends.
- **Work From Home % by Day**: Visualizes work-from-home patterns.
- **Sick Leave % by Day**: Highlights sick leave trends.
- Identifies specific days:
  - Most people worked from home.
  - Most people worked at the office.
  - Most people took sick leave.

## Tools Used

- **Power Query**: Data import, cleaning, and transformation.
- **DAX (Data Analysis Expressions)**: Created measures for advanced calculations.
- **Power BI**: Interactive dashboards for data visualization.

## Key Insights

1. Identified employee working preferences and trends.
2. Analyzed sick leave percentages on a monthly basis.
3. Gained insights into peak work-from-home and sick leave days.

## How to Use

1. Clone the repository to your local system:
   ```bash
   git clone <repository-link>