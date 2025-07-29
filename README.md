# Jumia Market Demand Analysis

## TABLE OF CONTENT
- [PROJECT OVERVIEW](# Market Demand Analysis -overview)
- [DATA SOURCE](#data-source)
- [LANDING PAGE](#landing-page)
- [TOOLS](#tools)
- [OBJECTIVES/KEY PERFORMANCE INDICATORS](#objectives/key-performance-indicators)
- [DATA CLEANING](#data-cleaning)
- [DATA PREPROCESSING](#data-preprocessing)
- [DATA ANALYSIS](#data-analysis)
- [DASHBOARD](#dashboard)
- [INSIGHTS](#insights)
- [RECOMMENDATIONS](#recommendations)

### PROJECT OVERVIEW
This analysis examines 100 selected products from jumia website. It aims to identify high-performing categories based on review volume and average rating for customer engagement and customer satisfaction.

### DATA SOURCE & EXTRACTION PROCESS
The dataset used in the analysis was sourced by scraping Jumia website using Jumia product scraper extension and the final output was saved as a CSV file for  analysis.

### LANDING PAGE
This explains each columns in the dataset as follows:
- Product Name: The title or name of the product listed in Jumia.
- Current Price: The Price at which the product is currently being sold.
- Original Price: The original (pre-discount) price of the product.
- Discount: The percentage reduction between the original and current price.
- Brand: The Company or label associated with the product.
- Ratings: The average customer satisfaction score(typically out of 5).
- Reviews count: The number of customer reviews the product has received (Customer engagement).
- Product Category: The category the product falls under (e.g. Electronics, beauty & health)
 
### TOOLS
  The tools used for this project are;
  - Microsoft Excel
  - Microsoft Power Bi
  - Microsoft Power point
 
 ### OBJECTIVES/KEY PERFORMANCE INDICATORS
- OBJECTIVES
To analyze customer interest and satisfaction across product categories using review count and average rating. The goal is to identify high-demand and high-engagement categories to inform category prioritization and pricing strategies for MyOnlineShop.


  ### DATA CLEANING
 Data Cleaning Process using Power Query.
- I handle null values changing null to 0 for my review count to indicate no engagement.
- I Cleaned Average rate by leaving null as null because changing it 0 would mean poor rating
- I cleaned inconsistent writing formats to normalize data.
- I combined all my files to a single datasets using the combine and transform when loading my datasets into PowerBI.


### DATA PREPROCESSING
- Calculation of weighted score was gotten by using 60% normalized average reviews and 40% normalized average rating.


  ### DATA ANALYSIS
Key Performance Indicators (KPIs):
	-	Average Rating: 4.07
  - Average Review Count:459.81
	- Average Discount:28%
	- Weighted Score: 18.44
	- Total Review Count: 583k


### DASHBOARD



### INSIGHTS
- Weighted Score by Product Category:
Supermarket and Gaming categories have the highest weighted scores, showing strong customer engagement and satisfaction. Most other categories perform similarly, scoring just slightly lower. The score ranges from (18-20).

- Average Review by Product Category:
Phones & Tablets show the highest customer engagement(2,025) then health-beauty (1,116) based on review count, while Gaming and Baby Products have the lowest.

- Average Rating by Product Category:
	All  product categories maintain a high average rating (3.94 – 4.36), showing strong customer satisfaction overall and Supermarket has the highest customer satisfaction   (4.36), while Phones & Tablets have the lowest (3.94).


- Average Discount by Product Category:
Computing (40%) and Phones & Tablets (34%) have the highest average discounts likely to attract buyers, clear inventory, or compete in crowded markets. Supermarket and Appliances have smaller discounts.

- Product Category by Average Review & Average Rating:
⦁	Phones & Tablets have the highest review count but the lowest ratings indicating high engagement but low customer satisfaction.
⦁	Baby Products have a very low review count (26.69) but a good rating (4.08), suggesting low visibility but satisfied customers.
⦁ Supermarket has the highest average rating (4.36) but low engagement.


### RECOMMENDATIONS
⦁	Focus on high performing categories like Appliances and electronics so as to offer opportunities.
⦁	Focus marketing on high- engagement categories for promotions. e.g Phone & tablets 
⦁	Leverage discounts strategically to make more sales and use it to clear underperforming product.
⦁	Customer satisfaction for all products should be a top priority.


