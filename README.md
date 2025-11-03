# Analysis of Myntra Apparel

##  Project Overview
This project is a comprehensive data analysis case study of Myntra's apparel dataset. The goal was to transform raw, messy data into actionable business insights concerning **pricing strategies, discount patterns, customer ratings, and inventory management**. Leveraging **Microsoft Excel**, this project demonstrates a complete workflow from data cleaning and preparation to advanced analysis and dynamic reporting.

> **Dataset Link:** https://drive.google.com/file/d/1CDaWFvkccjdUw1E_gipTKOfMqiHNhNQL/view

##  Business Problem
As a data analyst at Myntra, the core task was to analyze apparel data to help the management team:
*   Identify pricing trends and effective discount patterns.
*   Assess the relationship between customer ratings and product value.
*   Examine size availability to ensure alignment with customer demand and maximize sales potential.

##  Project Execution & Methodology

### A. Data Cleaning & Preparation
The foundation of any robust analysis is clean data. The following steps were taken to ensure data integrity:
*   **Removed Duplicate Values:** Ensured each product entry was unique to maintain accuracy in all calculations.
*   **Standardized DiscountOffer Column:** Converted all discount values (both flat rates and percentages) into a uniform **percentage format**, enabling consistent analysis.
*   **Imputed Missing Discount Prices:** Identified rows with null `DiscountPrice` and `DiscountOffer` values and filled them using the **category-wise average discount**, ensuring no data gaps.
*   **Handled Null Values in SizeOption:** Checked for and replaced any null values in the `SizeOption` column with **"Not Available"** to maintain dataset completeness.

### B. Data Analysis & Business Insights
Key metrics were calculated to uncover strategic insights:
*   **Premium for Quality:** Calculated the average original price for products with a rating greater than 4, revealing that higher-rated items command a significantly higher price.
*   **Aggressive Discount Strategy:** Counted the total number of products with a discount offer greater than **50% OFF**, highlighting a key volume-driving sales tactic.
*   **Core Size Analysis:** Determined the number of products available in size **"M"**, confirming it as a high-demand, core inventory size.
*   **Discount Segmentation:** Created a new column to label products as **"High Discount"** or **"Low Discount"**, enabling easy segmentation for further strategy analysis.

### C. Data Retrieval & Lookup
Advanced Excel functions were employed to build dynamic data retrieval tools:
*   **VLOOKUP/XLOOKUP:** Used to instantly retrieve the brand, price, and rating for a specific product (e.g., ID `11226634`).
*   **INDEX & MATCH:** Combined these functions to accurately find the `DiscountPrice` for a given product ID (e.g., `6744434`), demonstrating a flexible alternative to VLOOKUP.
*   **Nested XLOOKUP Dashboard:** Built an interactive tool that allows users to select any Product ID and column name to retrieve the corresponding value, showcasing efficient and user-friendly data querying.

##  Technologies & Skills
*   **Software:** Microsoft Excel
*   **Key Functions:** `XLOOKUP`, `VLOOKUP`, `INDEX & MATCH`, `AVERAGEIF`, `COUNTIF`, `IF`, `UNIQUE`
*   **Core Competencies:** Data Cleaning, Data Standardization, Business Intelligence, Trend Analysis, Dashboard Creation

##  Key Insights & Impact
The analysis provided actionable insights that can directly influence Myntra's business strategy:
*   **Pricing Strategy:** Confirmed a strong correlation between high product ratings and the ability to command premium prices.
*   **Sales Strategy:** Quantified the extensive use of deep discounts (>50% OFF), identifying it as a central pillar of the sales and customer acquisition strategy.
*   **Inventory Management:** Highlighted the critical importance of maintaining strong stock levels for size "M" to meet customer demand and prevent lost sales.

##  Mentorship
This project was completed under the valuable guidance of **Bhawani Singh** at **WsCube Tech**. His mentorship was instrumental in navigating the challenges of data analysis and reinforcing industry-best practices.
