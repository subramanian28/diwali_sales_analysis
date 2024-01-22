# Diwali Sales Analysis

## Introduction

This documentation presents a comprehensive analysis of sales data collected during the Diwali festival. The dataset includes information about customers, products, orders, and various demographic details. The primary objective of this analysis is to improve customer experience and increase revenue by extracting meaningful insights from the sales data.

## Data Loading and Cleaning

The initial step involved loading the dataset into a Pandas DataFrame. The dataset, named 'Diwali Sales Data,' contained 11,251 entries with 15 columns. These columns included information such as User_ID, Customer Name, Product_ID, Gender, Age Group, Age, Marital Status, State, Zone, Occupation, Product Category, Orders, Amount, and two unnamed columns.

To ensure a focused analysis, irrelevant or blank columns such as 'Status' and 'unnamed1' were dropped. Additionally, null values in the 'Amount' column were addressed by removing the corresponding rows. Data types were appropriately adjusted, with the 'Amount' column converted to integers.

## Exploratory Data Analysis (EDA)

### Gender Analysis

A bar chart was plotted to visualize the distribution of purchases based on gender. The analysis revealed that the majority of buyers were female, and their purchasing power exceeded that of male customers.
![image](https://github.com/no37no37/diwali_sales_analysis/assets/132648428/0e1feda4-69dc-4d5e-807a-091ea09b26e1)


### Age Group Analysis

A count plot and total amount visualization were generated to understand the distribution of purchases across different age groups. The findings indicated that the most active buyers were females in the 26-35 age group.
![image](https://github.com/no37no37/diwali_sales_analysis/assets/132648428/e31219c5-9aea-42d2-a83a-5bfaa5537710)


### State-wise Analysis

The analysis extended to examining the top 10 states contributing to both total orders and total sales. Uttar Pradesh, Maharashtra, and Karnataka emerged as significant contributors to both categories.
![image](https://github.com/no37no37/diwali_sales_analysis/assets/132648428/10407177-12ee-4a45-bfd8-ae19db6e189b)
![image](https://github.com/no37no37/diwali_sales_analysis/assets/132648428/a34c5ec8-5d21-47dc-8d64-f4d488bc724e)


### Marital Status and Occupation Analysis

Bar charts were used to explore the impact of marital status on purchasing behavior. Married women were identified as a prominent customer segment with high purchasing power. Furthermore, the occupation-wise analysis revealed that customers working in IT, Healthcare, and Aviation sectors were predominant.

![image](https://github.com/no37no37/diwali_sales_analysis/assets/132648428/1cdf9148-3c47-468c-963c-9449582ca511)

![image](https://github.com/no37no37/diwali_sales_analysis/assets/132648428/bc795531-d24c-4f49-b9c7-9b42da345561)


### Product Category and Product ID Analysis

Sales data was dissected based on product categories and specific product IDs. The most sold products belonged to the Food, Clothing, and Electronics categories.
![image](https://github.com/no37no37/diwali_sales_analysis/assets/132648428/83d1a5c8-3ccb-47d0-adaf-8b058bf4a3a7)


## Conclusion

The analysis concludes that individuals in the age group of 26-35, particularly married women, residing in states such as Uttar Pradesh, Maharashtra, and Karnataka, and working in sectors like IT, Healthcare, and Aviation, are more likely to purchase products from categories such as Food, Clothing, and Electronics.

## Recommendations

- Targeted marketing campaigns could focus on the identified demographic segments to maximize sales.
- Inventory management strategies can be adjusted to meet the demand for popular product categories.
