# Vrinda Store Annual Sales

## Problem Statement

Vrinda Store wants to create an annual sales report for 2022. So, that they can understand their customers and grow more sales in 2023.


### Steps followed 

- Step 1 : Analyzing Data
  - Dataset is an excel (xlsx) file, analyse data if it is enough to solve our problem.

- Step 2 : Data Cleaning 
  - Fiters were applied to the columns to check the null or duplicate values.
  - Checked the inconsistent data. For instance, in the gender column, the letters "M" and "Men" stand for men, and the letters "W" and "Women" stand for women. For consistency, either use 'M' and 'W' or 'Men' and 'Women'.

- Step 3 : Data Processing
  - Based on requirements, some calculation were done which would be helpful in Analysis. 
  - Created a new column named "Age Group" using the existing "Age" column. 
  Below is the formula used:
       
        =IF(E2>=50,"Senior", IF(E2>=30,"Adult", "Teenager"))
  where E2 is a cell of "Age" column 
  - Created a new column named "Month" using the existing "Date" column. 
  Below is the formula used:

        =TEXT(G2,"mmm")
  Where G2 is a cell of "Date" column

  "mmm" is for short month name e.g. Dec 

  "mmmm" is for long name e.g. December


- Step 5 : Data Analysis
  - Pivot table was created for data analysis and then it was represented in the form of visualizations.
  -  Clustered column chart was used to visualize orders vs sales.
  - Pie chart was used to visualize sales on different channels, order satus and sales among men and women.
  - Bar chart was used to visualize top 5 states with maximum sales.
  - Clustered column was used to visualize Age vs Gender.


 # Report Snapshot

![Report_img](https://github.com/vinodsrawat/Vrinda-Strore-Annual-Excel-Report/assets/161686865/6a68f05e-c6e6-4cbc-854d-1b33e9e42139)

# Insights

Following inferences can be drawn from the report;
								
1. Women are more likely to buy compared to men (~65%)								
2. Uttar Pradesh, Telangna and Tamil Nadu are the top 3 states								
3. Adult age (30-49 years) grroup is maximum contributing (~50%)								
4. Amazon, Flipkart and Myntra are the most contributing (~80%)								
								
# Final Conclusion to improve Vrinda Store Sales								
Target women customers of adult age group (30-49 years) living in Uttar Pradesh, Telangna and Tamil Nadu by showing ads/offers/coupons available on Amazon, Flipkart and Myntra.
