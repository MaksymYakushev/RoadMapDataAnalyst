# RoadMap for Data Analyst

The Data Analyst Roadmap is a comprehensive guide for those who aspire to become professional data analysts. It combines theoretical knowledge and practical skills, providing a complete set of tools for successfully entering the field of data analytics. We will use the roadmap from https://roadmap.sh.

[RoadMap](https://github.com/MaksymYakushev/RoadMapDataAnalyst/blob/main/Data/data-analyst-roadmap.pdf)  

# Table of Contents
- [Introduction](#introduction)
  - [What is Data Analytics](#what-is-data-analytics)
  - [Types of Data Analytics](#types-of-data-analytics)
- [Key Concepts of Data](#key-concepts-of-data)
- [Analysis / Reporting with Excel](#analysis--reporting-with-excel)
  - [Learn Common Functionsl](#learn-common-functions)
  - [Charting](#charting)
  - [Pivot Tables](#pivot-tables)
  - [Useful Links](#useful-links)
- [Learn SQL](#learn-sql)


# Introduction

## What is Data Analytics
Data analytics is the process of examining, cleaning, transforming, and modeling data to discover useful information, draw conclusions, and support decision-making. It involves various techniques and tools to analyze raw data and derive insights that can be used for improving business processes, making strategic decisions, and gaining a competitive edge.

## Types of Data Analytics
Data analytics can be categorized into four main types, each serving a different purpose and providing different insights:

1. Descriptive Analytics. Summarize and describe the main features of a dataset. Includes basic statistical measures like mean, median, mode, standard deviation, and visualizations such as histograms, bar charts, and pie charts. Understanding what has happened over a given period of time. For example, reporting on monthly sales figures or website traffic statistics.

2. Diagnostic Analytics: Understanding why something happened by examining data more deeply. Involves data mining, correlation analysis, and drill-down techniques to uncover patterns and relationships. For example, identifying the reasons behind a decline in sales or an increase in customer churn.

3. Predictive Analytics. Forecast future events based on historical data. Utilizes machine learning algorithms, statistical models, and predictive modeling techniques such as regression analysis, time series analysis, and classification. For example, predicting future sales trends, customer behavior, or potential risks. For example, predicting which customers are likely to purchase a product.

4. Prescriptive Analytics. Recommend actions based on the analysis and predictions. Combines predictive models with optimization algorithms and decision analysis to suggest the best course of action. For example, recommending inventory levels, optimizing supply chain operations, or personalizing marketing campaigns. For example, suggesting the best pricing strategy for maximizing revenue.

Each type of data analytics builds on the previous one, adding more depth and value to the insights gained from the data. Together, they provide a comprehensive approach to understanding and leveraging data for better decision-making.

# Key Concepts of Data
In the realm of data analysis, understanding some key concepts is essential. Data analysis is the process of inspecting, cleansing, transforming, and modeling data to discover useful information and support decision-making. In the broadest sense, data can be classified into various types like nominal, ordinal, interval and ratio, each with a specific role and analysis technique. Higher-dimensional data types like time-series, panel data, and multi-dimensional arrays are also critical. On the other hand, data quality and data management are key concepts to ensure clean and reliable datasets. With an understanding of these fundamental concepts, a data analyst can transform raw data into meaningful insights.

## Data Collection
In data analysis, the collection process is crucial. It involves systematically gathering and measuring information on specific variables, enabling data analysts to address relevant questions and assess outcomes. This initial step is fundamental, as it involves the first interaction with raw data, which is later transformed into actionable insights. The success of data analysis depends largely on the quality and quantity of the collected data. Various methods and tools are used for data collection, such as surveys, observations, experiments, or online data scraping, depending on the type of data required. It is essential to conduct this process with clear objectives and careful planning to ensure accuracy and relevance in subsequent analysis and decision-making stages.

## Cleanup
Data cleanup is a vital part of a Data Analyst’s job. This process entails inspecting, cleaning, transforming, and modeling data to uncover valuable information, draw conclusions, and support decision-making. Effective data cleanup is essential for producing accurate and meaningful insights, which in turn lead to better-informed business decisions. A thorough knowledge of data cleanup methods and techniques is an indispensable skill for any Data Analyst. Therefore, it is crucial to prioritize data quality by ensuring integrity, accuracy, and consistency throughout the data cleanup process.

## Exploration
In data analytics, data exploration is a crucial practice that data analysts use to comprehend and interpret data effectively. This process generally involves detecting patterns, identifying anomalies, examining underlying structures, and testing hypotheses. It is often carried out using descriptive statistics, visual techniques, or advanced algorithms. Data exploration is a foundational step for any data analyst, guiding the direction of subsequent analysis or modeling. This concept is essential for navigating the complexities and uncertainties of data, thereby enhancing decision-making across various fields such as business, finance, healthcare, and social sciences.

## Visualization
Data visualization is a crucial skill for any data analyst. It involves converting complex raw data into graphical formats, making it easier to understand large datasets, trends, outliers, and key patterns. Whether through pie charts, line graphs, bar graphs, or heat maps, data visualization techniques not only simplify data analysis but also enhance the communication of findings. This concept highlights the importance of presenting data in an accessible and visually appealing way to support data-driven decision-making within an organization.

## Statistical Analysis
Statistical analysis is fundamental to the daily work of a data analyst. It involves collecting, examining, interpreting, and presenting data, allowing analysts to discover patterns, trends, and relationships, derive insights, and support decision-making across various fields. By applying statistical concepts, data analysts can turn complex datasets into comprehensible information that organizations can use for actionable insights. This essential aspect of data analysis enables analysts to create predictive models, conduct trend analyses, and provide valuable business insights, making it indispensable in data analytics. Mastering statistical methodologies is crucial for data analysts to effectively interpret the large volumes of data they manage.

## Machine Learning
Machine learning, a branch of artificial intelligence, is an essential tool for data analysts. It enables systems to automatically learn, improve from experience, and make decisions without explicit programming. For data analysts, machine learning is crucial for uncovering hidden insights, recognizing patterns, and making predictions from large datasets. By employing various algorithms and models, data analysts can transform raw data into valuable information, making machine learning a pivotal aspect of data analysis.

# Analysis / Reporting with Excel
Excel is a powerful tool used by data analysts globally for storing, manipulating, and analyzing data. It provides a wide range of features, including pivot tables, graphs, and a robust suite of formulas and functions, enabling efficient handling of large datasets. Data analysts employ Excel for various tasks, from basic data entry and cleaning to complex statistical analysis and predictive modeling. Proficiency in Excel is often essential for data analysts, as its versatility and widespread use make it an invaluable asset in data analysis.

## Learn Common Functions
**IF function** 

The IF function is a premade function in Excel, which returns values based on a true or false condition. It is typed =IF and has 3 parts:
```plaintext
=IF(logical_test, [value_if_true], [value_if_false])
```
The condition is referred to as logical_test, which can check things like:
- If a number is greater than another number `>`
- If a number is smaller than another number `<`
- If a number or text is equal to something `=`

**DATEIF function**

Using this function while working on your spreadsheet can help you gain insight into date and time differences between two dates. 
```plaintext
=DATEDIF(start_date, end_date, unit)
```
The DATEDIF function includes the following arguments:
- `start_date` – This is a required argument. As the name suggests, it is the initial date of the period.
- `end_date` – This is also a required argument. It represents the last, or ending, date of the period.
- `unit` – The time unit in which we want the information.

**VLOOKUP / HLOOKUP functions**

The VLOOKUP function makes Excel search for a certain value in a column (the so called ‘table array’), in order to return a value from a different column in the same row. The V in VLOOKUP stands for "Vertical".
```plaintext
=VLOOKUP(lookup_value, table_array, column_index_num, [range_lookup])
```
- `lookup_value` - The value to look for in the first column of a table.
- `table_array` - The table from which to retrieve a value.
- `column_index_num` - The column in the table from which to retrieve a value.
- `range_lookup` - [optional] TRUE = approximate match (default). FALSE = exact match.

Use HLOOKUP when your comparison values are located in a row across the top of a table of data, and you want to look down a specified number of rows. Use VLOOKUP when your comparison values are located in a column to the left of the data you want to find. The H in HLOOKUP stands for "Horizontal".
```plaintext
=HLOOKUP(lookup_value, table_array, row_index_num, [range_lookup])
```
- `lookup_value` - The value to look up.
- `table_array` - The table from which to retrieve data.
- `row_index` - The row number from which to retrieve data.
- `range_lookup` - [optional] - A Boolean to indicate exact match or approximate match. Default = TRUE = approximate match.

**REPLACE / SUBSTITUTE functions**

The Excel REPLACE function replaces characters specified by location in a given text string with another text string. For example `=REPLACE("XYZ123",4,3,"456")` returns `"XYZ456"`.
```plaintext
=REPLACE(old_text, start_num, num_chars, new_text)
```
- `old_text` - The text to replace.
- `start_num` - The starting location in the text to search.
- `num_chars` - The number of characters to replace.
- `new_text` - The text to replace old_text with

The Excel SUBSTITUTE function replaces text in a given string by matching. For example `=SUBSTITUTE("952-455-7865","-","")` returns `"9524557865"`; the dash is stripped. SUBSTITUTE is case-sensitive and does not support wildcards.
```plaintext
=SUBSTITUTE(text, old_text, new_text, [instance_num])
```
- `text` - The text to change.
- `old_text` - The text to replace.
- `new_text` - The text to replace with.
- `instance` - [optional] The instance to replace. If not supplied, all instances are replaced.

**UPPER / LOWER / PROPER functions**

The Excel UPPER function converts a text string to all uppercase letters. Numbers, punctuation, and spaces are not affected.
```plaintext
=UPPER(text)
```
- `text` - The text to convert to uppercase.

The Excel LOWER function converts a text string to all lowercase letters. Numbers, punctuation, and spaces are not affected.
```plaintext
=LOWER(text)
```
- `text` - The text that should be converted to lower case.

The Excel PROPER function capitalizes each word in a given text string. Numbers, punctuation, and spaces are not affected.
```plaintext
=PROPER(text)
```
- `text` - The text that should be converted to proper case.

**CONCAT function**

The Excel CONCAT function concatenates (joins) values supplied as references or constants. Unlike the CONCATENATE function (which CONCAT replaces), CONCAT will accept a range of cells to join, in addition to individual cell references.
```plaintext
=CONCAT(text1, [text2], ...)
```
- `text1` - First text value, cell reference, or range.
- `text2` - [optional] Second text value, cell reference, or range.

**TRIM function**

The Excel TRIM function strips extra spaces from text, leaving only a single space between words and no space characters at the start or end of the text.
```plaintext
=TRIM(text)
```
- `text` - The text from which to remove extra space.

**AVERAGE function**

The Excel AVERAGE function calculates the average (arithmetic mean) of supplied numbers. AVERAGE can handle up to 255 individual arguments, which can include numbers, cell references, ranges, arrays, and constants.
```plaintext
=AVERAGE(number1, [number2], ...)
```
- `number1` - A number or cell reference that refers to numeric values.
- `number2` - [optional] A number or cell reference that refers to numeric values.

**COUNT function**

The Excel COUNT function returns a count of values that are numbers. Numbers include negative numbers, percentages, dates, times, fractions, and formulas that return numbers. Empty cells and text values are ignored.
```plaintext
=COUNT(value1, [value2], ...)
```
- `value1` - An item, cell reference, or range.
- `value2` - [optional] An item, cell reference, or range.

**SUM function**

The Excel SUM function returns the sum of values supplied. These values can be numbers, cell references, ranges, arrays, and constants, in any combination. SUM can handle up to 255 individual arguments.
```plaintext
=SUM(number1, [number2], [number3], ...)
```
- `number1` - The first value to sum.
- `number2` - [optional] The second value to sum.
- `number3` - [optional] The third value to sum.

**MIN / MAX function**

The Excel MIN function returns the smallest numeric value in the data provided. The MIN function ignores empty cells, the logical values TRUE and FALSE, and text values.
```plaintext
=MIN(number1, [number2], ...)
```
- `number1` - Number, reference to numeric value, or range that contains numeric values.
- `number2` - [optional] Number, reference to numeric value, or range that contains numeric values.

The Excel MAX function returns the largest numeric value in the data provided. MAX ignores empty cells, the logical values TRUE and FALSE, and text values.
```plaintext
=MAX(number1, [number2], ...)
```
- `number1` - Number, reference to numeric value, or range that contains numeric values.
- `number2` - [optional] Number, reference to numeric value, or range that contains numeric values.

## Courses on Datacamp:
Introduction to Excel / Google Sheets: https://app.datacamp.com/learn/courses/introduction-to-google-sheets

Certificate

Intermediate Excel / Google Sheets: https://app.datacamp.com/learn/courses/intermediate-google-sheets

Certificate

## Charting
## Pivot Tables
## Useful Links
Documentations for Excel / Google Sheets: https://exceljet.net/

Courses for Excel / Google Sheets: https://app.datacamp.com/learn/courses?technologies=10

# Learn SQL
