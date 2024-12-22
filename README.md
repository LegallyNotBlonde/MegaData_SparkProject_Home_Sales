# Home Sales Analysis: Big Data Project Overview

This project demonstrates the application of **PySpark** and **SparkSQL** to analyze large-scale home sales data. The goal was to extract insights and evaluate performance optimization techniques for handling extensive datasets.

[Google Colab Link](https://colab.research.google.com/drive/1JAqXeZ72H8PeUpzbIQnDB31JAs0zDSQV#scrollTo=G_Vhb52rU1Sn) - *View-only access to the executed code*.

## Project Objectives

The analysis aimed to calculate key metrics, including:

* The average price of four-bedroom homes sold annually.
* Pricing trends for homes with specific features, such as three bedrooms, three bathrooms, two floors, and over 2,000 square feet.
* Average home prices categorized by "view" rating, focusing on properties exceeding $350,000.
___

## Approach
1. **Data Preparation:** 
* Set up the environment and imported necessary libraries.
* Loaded the dataset into a Spark DataFrame and created a temporary SQL table for seamless querying.

2. **Performance Optimization:**

* Cached the SQL table and compared query runtimes with and without caching.
* Partitioned the dataset by the date_built column and saved it as Parquet files to enhance efficiency.

3. **Analysis and Insights:**

* Conducted SQL queries to derive trends in home pricing and evaluate features influencing property values.
* Assessed the runtime of operations to validate performance improvements using partitioned and cached data.

___

## Technologies and Skills
* **Big Data Tools:** PySpark, SparkSQL.
* **Data Processing:** Partitioning, caching, and optimizing large datasets.
* **SQL:** Writing efficient queries for exploratory analysis and performance evaluation.
* **File Formats:**  Worked with CSV and Parquet for structured data storage.
___

## Purpose
This analysis leverages fictional data to demonstrate the ability to analyze historical trends and provide actionable insights for real estate stakeholders. It highlights changes in median home prices, pricing trends for high-demand properties, and market segments with significant appreciation. The project showcases the skills required to conduct similar or more extensive analyses on diverse real estate data, supporting investment decisions, development strategies, and market assessments.

