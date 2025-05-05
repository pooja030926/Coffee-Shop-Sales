
# Coffee Shop Analysis

## Problem Statement


The coffee shop lacks clear visibility into its sales performance, making it difficult to identify key trends and optimize business strategies. There is a need to analyze historical sales data and develop an interactive dashboard using Excel to uncover patterns in customer behavior, product popularity, and revenue fluctuations. By doing so, the goal is to generate actionable insights that support informed decision-making and drive overall business improvement.



## Objective

I'm working with Excel to study sales data from a coffee shop, aiming to uncover insights that boost business results. This involves examining customer buying patterns, peak shopping times, and store traffic. By cleaning and structuring the data, we can spot trends such as top-selling items, busiest hours, and differences in sales across days, months, and locations. Excel helps turn raw data into useful strategies for improvement.


## Tools Used

Microsoft Excel

## Recommended Analysis

  1.  How do sales vary by day of the week and hour of the day ?
  2.  Are there any peak times for sales activity ?
  3.  What is the total sales revenue for each month ?
  4.  How do sales vary across different store locations ?
  5.  What is the Average Price Per Order per ?
  6.  Which products are the best selling in terms of Quantity &   Revenue ?
  7.  How do sales vary by Product Category and Size ?


## Data Structure

File type : Excel   
Table : 1  
FIELDS : 11  
Records : 149,116  
Data Span : Jan 2023 – Jun 2023(6 months)  
(Source : Maven Analytics)

## Steps followed in this project:

- Cleaned, structured, and transformed raw sales data into an analyzable format in Excel to enable accurate metric calculations and serve as the foundation for dashboard creation.

**In Power Query Editor:**

* Reviewed all columns to understand data context and identify inconsistencies related to the coffee shop's operations.
* Split product size codes ("Sm", "Rg", "Lg") from the *product\_detail* column into a new *size* column for clarity (mapped as Small, Regular, and Large).
* Trimmed leading and trailing spaces across all columns to ensure data consistency.
* Transformed *transaction\_time* to retain only time in HH\:MM\:SS format by removing date values.
* Created a calculated column *Total\_bill* by multiplying *unit\_price* with *transaction\_qty* to compute sales per transaction.
* Extracted *day of the week*, *month name*, and *hour* from date/time fields to enable detailed temporal sales analysis.

**Create Pivot Tables:**
* Used pivot charts to quickly analyze data, spot trends, and easily build interactive dashboards.

![Image](https://github.com/user-attachments/assets/d9707898-f874-4cca-ac4a-11397814c79a)

## insights

* **Peak Sales Hours:** Sales peak between 8:00 AM and 10:00 AM, highlighting high customer activity during morning hours.

* **High-Performing Days:** Mondays and Fridays show the highest transaction volumes, suggesting increased demand at the start and end of the workweek.

* **Product Size Preference:** Large-sized drinks account for the highest share of sales, while small sizes contribute the least, indicating customer preference for larger servings.

* **Store Footfall Analysis:** All store locations exhibit comparable monthly footfall, suggesting uniform customer distribution and equal revenue potential across branches.

* **Category Contribution:** Beverages in the Coffee and Tea categories make up approximately 67% of total sales, with Coffee alone contributing around 39%.

* **Top-Selling Products:** Barista Espresso leads in sales volume, followed by Brewed Chai Tea, indicating strong customer preference for classic coffee and tea offerings.

## Final Result

![Image](https://github.com/user-attachments/assets/5b4157cf-8265-4112-a080-c24d0a721fef)


