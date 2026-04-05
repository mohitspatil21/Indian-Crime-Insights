# Indian-Crime-Insights
Developed an interactive Power BI dashboard to analyze crime data across India, identifying regional trends, crime distribution, and year-over-year growth. Applied data cleaning, transformation, and DAX calculations to generate actionable insights for data-driven decision-making.
# Project Overview
This project focuses on analyzing crime data across various states and districts of India using Power BI. The goal is to identify crime trends, patterns, and regional disparities to support data-driven decision-making for public safety.
# Objectives
- Analyze crime distribution across states and districts  
- Identify top crime categories and high-crime regions  
- Evaluate year-over-year crime growth  
- Highlight crimes against women and severity levels  
# Tools & Technologies
- Power BI  
- DAX (Data Analysis Expressions)  
- Power Query  
- Data Modeling (Snowflake Schema)
# Dataset
The dataset includes:
- Year  
- State  
- District  
- Crime Type  
- Total Crimes
- Data Is Provided on Government Crime Investigation Website
# Data Preparation
- Cleaned missing and inconsistent data  
- Removed duplicates and unnecessary columns  
- Standardized data formats  
- Transformed data using Power Query (Unpivoting, Renaming)
# Data Modeling
- Implemented a **Snowflake Schema**  
- Fact Table: `Fact_Crime`  
- Dimension Tables: `Dim_State`, `Dim_District`, `Dim_Crime_Category`  
- Established relationships for efficient analysis  
# DAX Measures
- **Total Crimes** = SUM(Fact_Crime[Total Crimes])  
- **YoY Crime Growth %**  
- **Crime Severity Index**  
- **Crimes Against Women %**  

# Dashboard Features
- 📌 KPI Cards (Total Crimes, Growth, Severity Index)  
- 📈 Trend Analysis (Year-wise crime patterns)  
- 📊 Crime Type Distribution (Bar & Donut Charts)  
- 🗺 Geographic Insights (State & District-level maps)  
- 🎛 Interactive Filters (Year, State, Crime Category)  
# Key Insights
- Identified top states and districts with highest crime rates  
- Highlighted most frequent crime types  
- Observed year-over-year growth trends  
- Analyzed proportion of crimes against women  
- Detected regions with high crime severity  
# Dashboard Preview
<img width="975" height="547" alt="image" src="https://github.com/user-attachments/assets/b2ff4c1a-3a13-4dab-8981-ea8e1f1f1ad5" />

<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/7abfd010-8eb3-42f3-8794-2d80fa4a6be1" />

<img width="975" height="543" alt="image" src="https://github.com/user-attachments/assets/8576500b-44fe-46ba-aa6c-f73b8530c494" />

<img width="975" height="750" alt="image" src="https://github.com/user-attachments/assets/9e670829-64ae-4f7b-b37b-119f29565fdb" />

# Conclusion
This project demonstrates how Power BI can be used to transform raw data into meaningful insights. The dashboard helps in understanding crime patterns and supports better decision-making for improving public safety.
# Files Included
- Power BI Dashboard (.pbix)  
- Dataset (CSV)  
- Project Documentation  
# Author
**Mohit Patil**  
TY IT Undergraduate Student  
Data Analyst | SQL | Python | Power BI

# Contact
- LinkedIn: *(https://www.linkedin.com/in/mohit-patil-832406400?utm_source=share_via&utm_content=profile&utm_medium=member_android)*  
- Email: *(mohitspatil.21@gmail.com)*  
