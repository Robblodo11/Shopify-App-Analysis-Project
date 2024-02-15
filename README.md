# Shopify-App-Analysis-Project
## Table of Contents
### Introduction
### The Data
### Part 1: App Landscape
* App Landscape Sheet
* KPI Card: Unique Number of Apps
* Line Chart: Review Count vs Lastmod Date
* Scatterplot: Reviews Count vs Average Rating
### Part 2: Reviews
* Reviews Sheet
* KPI Card: Average Value of Helpful Reviews
* Scatterplot: Average Rating vs Developer Answered
### Part 3: App Reviews
* App Reviews Sheet
* Bar Chart: Sum of Rating by Developer
* Bar Chart: Helpful Review Average by Developer
* Bar Chart: Most Responsive Developers


### Introduction
* You have been hired to review the landscape of apps on the Shopify platform, using data scraped from publicly available Shopify websites. This project aims to figure out the key factors that contribute to the success of a Shopify app.

### The Data
* The shopify.xlsx dataset contains public data scraped from the Shopify App Store. It includes four tables:
  * apps: Details of the apps on Shopify apps marketplace.
  * apps_categories: Join tables to connect apps with categories.
  * categories: Categories of the apps. Each app has multiple categories.
  * reviews: Each review (row) contains information on user opinion about the related app (rating and comment). Also, it contains the response from the developer if present.
    
### Part 1: App Landscape
* App Landscape Sheet
  * New sheet in Power BI (.pibx) file for analyzing app landscape.
* KPI Card: Unique Number of Apps
  * Counts the unique number of apps.
* Line Chart: Review Count vs Lastmod Date
  * Sum of the review count on the Y-axis vs the lastmod date on the X-axis.
* Scatterplot: Reviews Count vs Average Rating
  * Reviews count on the X axis and the average rating on the Y axis with interpretation.

### Part 2: Reviews
* Reviews Sheet
  * New sheet in the Power BI file for analyzing reviews.
* KPI Card: Average Value of Helpful Reviews
  * Average value of the new helpful_reviews column.
* Scatterplot: Average Rating vs Developer Answered
  * Comparison of the average rating on the Y-Axis by the value of the developer_answered column on the X-Axis.

### Part 3: App Reviews
* App Reviews Sheet
  * New sheet in the Power BI file for analyzing app reviews.
* Bar Chart: Sum of Rating by Developer
  * Developer on the X-Axis and the sum of rating on the Y-Axis.
* Bar Chart: Helpful Review Average by Developer
  * Developer on the X-Axis against the helpful_review average on the Y-Axis.
* Bar Chart: Most Responsive Developers
  * Developer from the apps table and the developer_answered column with a filter for rows where reviews_count is greater than 500.
