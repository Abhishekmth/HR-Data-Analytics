# HR ANALYTICS DASHBOARD

## Table of contents


   • [project overview](#project-overview)  
   • [Data Sources](#data-sources)  
   • [Recommendations](#recommendations)   
   • [Tools](#tools)  
   • [Data Cleaning](#data-cleaning)   
   • [Exploratory Data Analysis](#explanatory-data-analysis)    
   • [Data Analysis](#data-analysis)   
   • [results](#results)   
   • [recommendations](#recommendations)

# Sales-Dashboard

### Dashboard Link :(https://app.powerbi.com/links/T10zjSGu9z?ctid=67fd393b-d7f6-4f86-90cc-0623b59551e6&pbi_source=linkShare&bookmarkGuid=661aadd1-2c0c-4fce-bfc4-2442b5390682)

# project overview

   This data analysis project aims to provide insights about the HR analytics
   It shows detailed data analysis on employee working across different verticals, average salary, attrition, average working years
   It involves utilization of advanced analytical tools to uncover trends, patterns, and regional insights, facilitating informed decision-making and targeted strategies

###  Data sources

   The primary dataset used for analysis is the "HR_Analytics.csv" file, containing detailed information about each sale made by the company.

### Tools
   
   • Excel-Data Cleaning   
   • power BI- Creating DAX Functions, measures,reports

### Data Cleaning/Prepration

   In the initial data prepration phase, we performed the following tasks-  
    1.Data loading amnd inspection  
    2.Handling missing values - This is done by assigning all NULL values as 'others'
    3.Data cleaning and  formatting -Formatting of various columns like date is done. Relationships are build by pivots
    
### Exploratory Data Analysis(EDA)

   1.what is the overall sales trend?   
   2.which products are top sellers?     
   3.which product gets maximum discount?   


### Results
   The analysis results are summarised as follows:
   -'Overall Attrition% is currently at 17% and Attrition% for job role Sales Representatiove is significantly higher than other segments at 37.78%
   ![image](https://github.com/Abhishekmth/Sales-Data-Analysis/assets/64078831/1805fcbf-d16d-4b13-8539-a26a8e5f5d09)

   -Job Satisfaction share for HR is lesser than other positions
   ![image](https://github.com/Abhishekmth/Sales-Data-Analysis/assets/64078831/c30efc54-9c39-4512-bfc1-46406a557406)

   
   -Life sciences comprises of fairly bigger share in EducationField
   ![image](https://github.com/Abhishekmth/Sales-Data-Analysis/assets/64078831/6393b26c-5196-45ce-b28e-e2969fde60f9)
   

   -Average age of all the employees is 37 years
   ![image](https://github.com/Abhishekmth/Sales-Data-Analysis/assets/64078831/a475c813-1ff5-4e92-afbb-303fe1bec897)


### Recommendations

  Based on analysis, we recommend the following actions:
     -Focus is needed on HR Professional regarding job satisfaction .
     -Average salary for Technical professional is too low.
     -Imbalance in salaries i.e wide gap between maximum and minimum salary

### Limitations
   I had to remove all zero values from quantity and profit columns because they would have affected the accuracy of my conclusuions from the analysis . there are still a few
  outliners even after the omissions but even then we can sill see there is a positive trend.


