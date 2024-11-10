# Data-Engineering-and-warehousing-of-Motor-Vehicle-Collision-dataset-
## Project Overview
This project focuses on building a comprehensive ETL (Extract, Transform, Load) and data analysis pipeline for motor vehicle collision data from New York, Chicago, and Austin. The objective is to centralize, clean, and analyze this data to provide insights into collision patterns, accident frequency, and contributing factors. This analysis is aimed at aiding city officials and policymakers in making data-driven decisions to improve road safety.
## Workflow

![image](https://github.com/user-attachments/assets/ed9bf710-c2b6-4048-b5ed-5da1e1c0720b)

## Project Phases

### 1. Data Profiling and Dimensional Modeling
- **Data Profiling**: Conducted preliminary analysis of crash datasets using Python to understand data quality and unique characteristics for each city.
- **Dimensional Modeling**: Based on the given Business requirements, analyzing the data prepared the dimensional model for pipeline building
![image](https://github.com/user-attachments/assets/84c56233-ce53-48b2-af52-5211eb76d916)

### 2. ETL building
 - **Data Extraction**:  Designed and constructed staging tables in SQL Server to establish a robust environment for handling raw data. Using Talend’s ETL tools, data loading from multiple sources was automated, allowing for seamless transformation and standardization to meet reporting requirements. Landing tables were built in Talend ETL, streamlining the integration of diverse data sources and simplifying the transformation process.
   
- **Data Tranformations**: Based on business requirements, fact calculations were performed using Talend ETL's t-map component. This allowed for efficient transformation, column mapping, and accurate alignment of data with reporting needs. The t-map component was configured to map columns effectively, ensuring that each data point was correctly assigned to its respective field in the target tables.

- **Data Loading** : After applying the necessary transformations, data was accurately loaded into the required dimension and fact tables in Microsoft SQL Server. This step ensured that the transformed data was organized and structured according to the project’s data model, enabling seamless access for reporting and analysis.
### 3. Visualization and Reporting

- **Tools Used**: Tableau and Power BI for creating visual dashboards.
 
- **Insights Provided using Tableau and Power BI**:\
    • How many accidents occurred in NYC, Austin and Chicago?\
    • Use your ideas on how best to present these values on the dashboard\
    • Which areas in the 3 cities had the greatest number of accidents?\
    • top 3 areas in each city\
    • How many accidents resulted in just injuries? (generated at 2 levels, 1 -> overall, 3 -> by city)\
    • How often are pedestrians involved in accidents? (generated at 2 levels, 1 -> overall, 3 -> by city)\
    • When do most accidents happen?\
    • seasonality report\
    • How many motorists are injured or killed in accidents? (generated at 2 levels, 1 -> overall, 3 -> by city)\
    • Which top 5 areas in 3 cities have the most fatal number of accidents?\
    • Time based analysis of accidents (Time of the day, day of the week, weekdays or weekends.)\ 
    • Fatality analysis\
    • Are pedestrians killed more often than road users?\
    • What are the most common factors involved in accidents

## Technologies Used
- **ETL Tool**: Talend, Alteryx Designer, Python(Ydata Profiling)
- **Database**: SQL Server
- **Data Analysis**: Python (Pandas, NumPy), SQL
- **Visualization**: Tableau, Power BI

## Conclusion
This project provides a robust foundation for analyzing motor vehicle collision data and generating actionable insights. Although data gaps in geographic and contributing factor information limit some analyses, the project demonstrates a scalable approach to data warehousing and analytics that can be expanded for additional datasets or cities.
