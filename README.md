# Home Sales Analysis: Big Data 

## Project Overview

This project utilizes **PySpark** and **SparkSQL** to analyze a large-scale, fictional real estate dataset. 
It demonstrates how big data tools can uncover valuable insights such as pricing trends, the impact of property features, and market segment performance while optimizing the handling of extensive datasets.

[Google Colab Link](https://colab.research.google.com/drive/1JAqXeZ72H8PeUpzbIQnDB31JAs0zDSQV#scrollTo=G_Vhb52rU1Sn) - *View-only access to the executed code*.

## Objectives

The analysis focused on:

* Identifying yearly pricing trends for various property types.
* Assessing the influence of specific property features (e.g., bedrooms, bathrooms, view ratings) on home prices.
* Evaluating the efficiency of data operations using caching and partitioning techniques.
___

## Approach
1. **Data Preparation:** 
Loaded data into a Spark DataFrame, reformatted columns, and created a temporary SQL table for analysis.

2. **Analysis:**
Conducted SQL queries to extract insights on pricing trends and feature impacts.

3. **Optimization:**
Evaluated performance improvements through partitioning and caching techniques.

___

## Technologies and Skills

* **Big Data Tools:** PySpark, SparkSQL.
* **Data Storage and Processing:** Partitioning, caching, CSV, and Parquet formats.
* **SQL Analysis:** Efficient queries for trend and feature analysis.

___
## Insights and Conclusions:

* **Pricing Trends:**
The pricing trends for 2-bedroom, 3-bedroom, and 4-bedroom houses show diverging patterns. 
While 2-bedroom and 3-bedroom homes have a steady upward trend in average prices, 4-bedroom homes experience a gradual decline over the years. This divergence likely reflects shifts in demand and affordability among buyers.
![Average Price of 2-3-4-Bedroom Houses by Year Sold](https://github.com/LegallyNotBlonde/MegaData_SparkProject_Home_Sales/blob/main/Visualization/avg_price_2_3_4_bedrooms.png)

* **Feature Impacts:** Homes with specific configurations (e.g., three bedrooms, three bathrooms) had stable pricing trends by year built, indicating steady demand for these features.
![Average Price by Year Built for 3-Bedroom, 3-Bathroom Homes](https://github.com/LegallyNotBlonde/MegaData_SparkProject_Home_Sales/blob/main/Visualization/avg_price_3b_3ba.png)
Illustrates steady pricing for this configuration, showing no significant impact of year built on prices during the analyzed period.

* **View Ratings:** Properties with high view ratings (e.g., 90+) commanded premium prices exceeding $1,000,000, suggesting a strong correlation between scenic views and property valuation. 
However, this relationship may not be causal; high-value properties in prime locations might inherently offer better views, driving both higher ratings and prices.

![Average Price by View Rating](https://github.com/LegallyNotBlonde/MegaData_SparkProject_Home_Sales/blob/main/Visualization/avg_price_by_view.png)
This bar chart illustrates the correlation between premium pricing and higher view ratings.
___
## Conclusion:
This analysis showcases the ability to extract actionable insights from large datasets, supporting real estate decisions such as pricing strategies, feature valuation, and market trend identification. 
It highlights the scalability of PySpark for handling and optimizing big data workflows.