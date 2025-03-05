# Analysis-of-Myntra-Apparel

# Project Overview
This project analyzes apparel data from Myntra, focusing on data cleaning, preparation, analysis, and lookup operations using Microsoft Excel. The project covers important aspects such as handling duplicates, filling missing values, categorizing discounts, and retrieving product information using powerful Excel functions like VLOOKUP, XLOOKUP, INDEX & MATCH.

Dataset Link:https://drive.google.com/file/d/1CDaWFvkccjdUw1E_gipTKOfMqiHNhNQL/view

# Data Cleaning and Preparation
Steps Performed:
&#8226; Removed duplicate records using the Remove Duplicates feature.

&#8226; Standardized the "DiscountOffer" column to ensure consistent formatting.

&#8226; Filled missing "DiscountPrice" values using the average discount price within the respective product category.

&#8226; Replaced all null values in the "SizeOption" column with "Not Available".

# Data Analysis Objectives
Key Insights Derived:

&#8226; Average Price Calculation
Calculated the overall average original price for products with ratings greater than 4 using AVERAGEIF.

&#8226; High Discount Products
Counted the number of products with discounts exceeding 50% OFF using COUNTIF.

&#8226; Size Availability Check
Counted the number of products available in size "M" using COUNTIF.

&#8226; Discount Classification
Added a "High Discount" or "Low Discount" label to each product using the IF function, based on whether the discount exceeded 50%.


# Lookup & Retrieval Tasks
Lookup Functions Applied

&#8226; Product Details Lookup
Used XLOOKUP and VLOOKUP to find the brand, price, and rating of a product with Product ID 11226634.

&#8226; Discount Price Lookup
Retrieved the DiscountPrice for Product ID 6744434 using a combination of INDEX and MATCH.

&#8226; Nested Lookup for Advanced Retrieval
Used nested XLOOKUP to fetch specific column details for a product based on its Product ID.



# Excel Techniques & Formulas Used

&#8226; Data Cleaning : Remove Duplicates, Text to Columns, IFERROR

&#8226; Analysis : AVERAGEIF, COUNTIF, IF

&#8226; Lookup Operations : VLOOKUP, XLOOKUP, INDEX, MATCH

&#8226; Conditional Formatting : Conditional Formatting for visual insights

# Conclusion
This project highlights how Excel's powerful functions can be leveraged to conduct comprehensive analysis of e-commerce datasets. By cleaning the data, applying analytical formulas, and retrieving insights through lookups, businesses can make data-driven decisions related to product pricing, discounting strategies, and inventory management.





 
