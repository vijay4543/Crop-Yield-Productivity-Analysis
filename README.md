# Crop-Yield-Productivity-Analysis🌾 
An end-to-end Microsoft Excel Data Analytics project focused on analyzing agricultural crop yield, productivity, regional performance, fertilizer usage, and time-based trends.

This project demonstrates practical data analyst skills including data cleaning, data preparation, Excel formulas, PivotTables, PivotCharts, slicers, KPI analysis, and dashboard design.

📌 Project Overview

The Crop Yield & Productivity Analysis project transforms raw agricultural data into an interactive Excel dashboard that helps users understand crop production and productivity patterns.

The dashboard is designed to answer questions such as:

Which states/regions have the highest total crop yield?

Which crops contribute the most to overall production?

How does crop yield change over time?

Which crop categories show better productivity?

Which regions or districts perform better?

How do fertilizer usage and agricultural inputs relate to yield?

Which crops have the strongest productivity performance?

The project follows a practical data-analysis workflow from raw dataset → cleaning → transformation → analysis → visualization → dashboard.

🎯 Purpose of the Project

The main purpose is to demonstrate how raw agricultural data can be converted into meaningful business-style insights using Excel.

Key objectives

Clean and standardize agricultural data.

Handle missing and duplicate records.

Standardize category/text fields.

Validate numerical and date fields.

Create useful calculated columns.

Analyze crop yield and productivity.

Compare performance across states, districts, and crops.

Identify trends over time.

Build an interactive Excel dashboard.

Present insights in a clear and professional format.

🔄 Project Workflow

Kaggle Dataset
      ↓
Raw Data Import
      ↓
Data Cleaning
      ↓
Duplicate Check
      ↓
Missing Value Check
      ↓
Text Standardization
      ↓
Data Validation
      ↓
Calculated Columns
      ↓
PivotTables
      ↓
PivotCharts
      ↓
Slicers / Filters
      ↓
Dashboard
      ↓
Agricultural Insights

🧹 Data Cleaning & Preparation

The dataset was reviewed and prepared before visualization.

1. Duplicate Check

Duplicate records were identified and reviewed to avoid double-counting during analysis.

2. Missing Value Check

Critical fields were checked for blank or missing values.

Examples:

Crop

Fertilizer Used

State

District

Area

Yield

Date/Year

Production-related fields

3. Text Standardization

Category-like columns were standardized for consistent analysis.

Columns included:

Crop

Fertilizer Used

District

State

Example Excel formula:

=PROPER(TRIM(A2))

This helps convert values such as:

rice
RICE
 rice

into:

Rice

4. Numerical Validation

Numerical columns were checked for:

Blank values

Invalid values

Zero values where inappropriate

Inconsistent formats

5. Date / Time Preparation

Existing Year and Month fields were used where available to analyze agricultural trends over time.

📊 Calculated Analysis

Yield per Acre / Productivity

Where Area and Total Yield are available:

=Total_Yield/Area

This creates a productivity measure that allows comparison between locations or crops of different sizes.

Example

If:

Total Yield = 5,000
Area = 10

Then:

Yield per Acre = 500

The exact formula should be adapted to the actual column positions in the workbook.

📈 Dashboard Analysis

The Excel dashboard presents agricultural information using multiple visualizations and interactive filters.

Main dashboard areas

1. Total Yield KPI

Shows the overall crop yield represented in the dataset.

2. Yield by State / Region

Compares total yield across geographical areas.

3. Crop Yield Summary

Highlights crops with higher and lower yield contributions.

4. Yield Trend Analysis

Uses time-based analysis to identify changes in yield across months, seasons, or years.

5. Yield by Category

Compares agricultural performance across crop/category groups.

6. Interactive Filters

Slicers/filters allow the user to dynamically explore the dashboard based on available dimensions such as:

State

District

Crop

Fertilizer

Year

Month

Category

🛠️ Tools & Technologies Used

Microsoft Excel

Used for the complete data-analysis workflow:

Data Cleaning

Data Validation

Excel Formulas

Sorting & Filtering

Conditional Formatting

PivotTables

PivotCharts

Slicers

Dashboard Development

KPI Analysis

Excel Functions Used

Examples include:

PROPER()
TRIM()
COUNTIF()
COUNTBLANK()
ISBLANK()
SUM()
AVERAGE()

Calculated metrics were also created using basic arithmetic formulas such as:

=Total_Yield/Area

📂 Dataset

Source

The agricultural dataset used for this project was obtained from Kaggle.

Kaggle Dataset: Comprehensive Tamil Nadu Agriculture Dataset

The dataset contains agricultural information useful for studying crop yield, productivity, rainfall, land usage, fertilizer use, districts, crops, and agricultural trends.

Kaggle source:

https://www.kaggle.com/datasets/kiruthikas005/comprehensive-tamil-nadu-agriculture-dataset

Note: If your downloaded dataset came from a different Kaggle page, replace the Kaggle link above with the exact dataset URL you used.

🧠 Data Analyst Skills Demonstrated

This project showcases the following practical skills:

Data Cleaning

Duplicate detection

Missing-value checking

Text standardization

Data validation

Category consistency

Data Transformation

Creating calculated columns

Creating productivity metrics

Preparing fields for analysis

Converting raw data into analysis-ready data

Data Analysis

Aggregation

Trend analysis

Comparative analysis

Regional analysis

Crop-level analysis

Productivity analysis

Data Visualization

KPI Cards

Bar Charts

Column Charts

Line Charts

Trend Charts

Interactive Slicers

Dashboard Layout

Business / Analytical Thinking

The project focuses not only on creating charts but also on answering meaningful analytical questions from agricultural data.

💡 Key Insights to Highlight

When presenting this project, focus on insights rather than only showing charts.

Examples:

Identify the highest-yielding states or regions.

Identify the top-performing crops.

Compare crop productivity across regions.

Identify periods with higher or lower yield.

Compare crop categories.

Identify unusual or low-performing observations.

Analyze whether fertilizer-related categories show differences in productivity.

Exact findings should be reported from the final cleaned dataset and dashboard values rather than assumed in advance.

🎥 Project Demonstration

A screen recording of the Excel dashboard is included as a project demonstration.

The recording shows:

Dashboard overview

KPI/summary sections

Charts and visualizations

Interactive filters/slicers

Raw data and analysis workflow

📁 Suggested Repository Structure

Crop-Yield-Productivity-Analysis/
│
├── README.md
│
├── Dataset/
│   └── agricultural_dataset.csv
│
├── Excel/
│   └── Crop_Yield_Productivity_Analysis.xlsx
│
├── Dashboard/
│   └── Crop_Yield_Dashboard.png
│
├── Demo/
│   └── Crop_Yield_Dashboard_Demo.mp4
│
└── Documentation/
    └── Project_Insights.pdf

🚀 Future Improvements

This project can be extended beyond Excel.

Power BI

The cleaned dataset can be imported into Power BI to create:

Interactive dashboards

Drill-through reports

Advanced DAX measures

Map visualizations

Dynamic KPIs

SQL

The dataset can also be loaded into MySQL to demonstrate:

Database creation

Data cleaning with SQL

GROUP BY analysis

JOIN operations

Subqueries

CTEs

Window functions

Python

Python can be used for:

Pandas-based data cleaning

Exploratory Data Analysis

Matplotlib visualizations

Statistical analysis

Crop-yield prediction

Machine Learning

A future version could predict crop yield using features such as:

Crop

State

District

Area

Fertilizer usage

Rainfall

Temperature

Historical yield

📌 Portfolio Value

This project demonstrates an important real-world data analyst workflow:

Raw Data → Clean Data → Transform → Analyze → Visualize → Communicate Insights

It is suitable as an entry-level Data Analyst / Excel Data Analyst portfolio project and demonstrates the ability to work with real-world categorical, numerical, geographical, and time-based agricultural data.

👨‍💻 Author

Vijay Kumar

Aspiring Data Analyst

Skills

Microsoft Excel

SQL

Python

Power BI

Data Cleaning

Data Visualization

Data Analysis

⭐ If you find this project useful

Feel free to explore the workbook, dashboard, and analysis workflow.

Suggestions and feedback are welcome!
