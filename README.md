# Analysis-of-Myntra-Apparel

# Project Overview
This project analyzes apparel data from Myntra, focusing on data cleaning, preparation, analysis, and lookup operations using Microsoft Excel. The project covers important aspects such as handling duplicates, filling missing values, categorizing discounts, and retrieving product information using powerful Excel functions like VLOOKUP, XLOOKUP, INDEX & MATCH.

Dataset Link: 
https://drive.google.com/file/d/1CDaWFvkccjdUw1E_gipTKOfMqiHNhNQL/view

# Data Cleaning and Preparation
Duplicate Removal: Identified and eliminated duplicate records to maintain data integrity.
Discount Formatting: Standardized the values in the DiscountOffer column for consistency.
Missing Values Treatment:
Filled missing DiscountPrice using the average discount price per category.
Replaced empty SizeOption values with "Not Available" to avoid gaps in analysis.Data Analysis Objectives

# Data Analysis Objectives
To generate meaningful insights, the following analytical tasks were performed:

Average Price Analysis: Calculated the average original price for products with ratings above 4 using AVERAGEIF.
Discount Analysis: Counted products offering more than 50% discount using COUNTIF.
Size Analysis: Determined the number of products available in size M.
Discount Classification: Added a new column to classify products as High Discount (above 50%) or Low Discount (50% or below) using the IF function.

# Lookup & Retrieval Tasks
Excel’s lookup functions were applied to quickly fetch product details based on Product IDs:

Product Details Retrieval: Used XLOOKUP to fetch brand, price, and rating for Product ID 11226634.
Discount Price Lookup: Retrieved DiscountPrice for Product ID 6744434 using a combination of INDEX and MATCH.
Nested Lookup: Implemented a nested XLOOKUP to dynamically pull column details based on product ID.

# Excel Techniques & Formulas Used

&#8226; Data Cleaning:Remove Duplicates, Text to Columns, IFERROR
Analysis:AVERAGEIF, COUNTIF, IF
Lookup Operations:VLOOKUP, XLOOKUP, INDEX, MATCH
Conditional Formatting : Conditional Formatting for visual insights

# Conclusion
This project highlights the power of Excel for quick and effective data analysis in the e-commerce domain. By leveraging its versatile functions, we were able to clean messy data, uncover insights, and retrieve product details efficiently — all crucial steps for data-driven decision-making in a competitive online retail environment.






 
