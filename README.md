# E-commerce_sales_analysis

### Project overview
This Data analysis project aim to provide insights into the sales performance based in lagos, in the 2nd and 3rd quarters of the year 2021. By analysing various aspect of the sales data, we seek to identify trends, make data-driven recommendations and gain a deeper understanding of the company's performance.

### Data Source
The dataset usedfor this analysis is the "Service Provider New Version.xlsx" file
[Download here](https://github.com/user-attachments/files/17993057/Service.Provider.New.Version.raw.xlsx)

### Tools
 - Excel - Data cleaning
    - [Dowload here](https://microsoft.com)
- MySQL-Data Analysis
- PowerBI - Data Visualization

###  Data Cleaning
In the preparation of the dataset for Analysis,we perform the following task:
1. Removal of duplicates
2. Handled missing values with VLOOKUP
3. Change values to the Appropriate formate

   ### Exploratory Data Analysis
    The data was explored to answer key questions such as:
   - What was the monthly sales trend?
   - what were  the top performing categories?
   - what were the peak sales period?

     ### Data Analysis

     ```MySQL
     SELECT payment_date, amount FROM service_provider_tables
     WHERE Category = 'betting'
     ```
     ### Dashboard
     
     ![Screenshot (3)](https://github.com/user-attachments/assets/6433b3b3-d761-4ef0-9e97-0ef389870fa3)

     ### Results/Findings

     ### Recomendations
     
