Project Overview

The primary objective was to create a centralized reporting tool to analyze revenue trends, customer spending behavior, and operational efficiency. By leveraging Excel’s advanced BI capabilities (Power Query and Power Pivot), the project provides a dynamic view of business health.

Development Methodology

The project followed a structured data pipeline to ensure data integrity and analytical depth:

1. Data Extraction (ETL Phase)

   ➤ Process: Extracted raw data from multiple source files (CSV/Excel) using Power Query Editor.

   ➤ Goal: Establish a reliable connection to data sources for seamless refreshing.

2. Data Cleaning

   ➤ Refinement: Utilized Power Query to remove null values, trim unnecessary white spaces, and resolve naming inconsistencies.

   ➤ Quality Control: Standardized date formats and category names to ensure accurate grouping during analysis.

3. Data Transformation

   ➤ Feature Engineering: Created new calculated columns within Power Query to enhance the dataset.

   ➤ Examples: Derived "Order Hour" from timestamps and categorized dates into specific "Occasions" (e.g., Diwali, Valentine's Day) to         facilitate seasonal analysis.

4. Data Modeling

   ➤ Architecture: Performed using the Power Pivot add-in.

   ➤ Relational Design: Established relationships between multiple tables (Sales, Products, Customers, and Calendar) to create a               cohesive Star Schema, allowing for complex cross-table analysis.

5. Data Analysis

   ➤ Computation: Developed Pivot Tables and used DAX (Data Analysis Expressions) to create measures such as Total Revenue, Total              Orders, and Average Customer Spend.

   ➤ Granularity: Analyzed performance by hour, day, and city to identify peak operational periods.

6. Dashboarding

   ➤ Visualization: Integrated various charts (Bar, Line, and Column) to represent the findings visually.

   ➤ Interactivity: Added Slicers for "Order Date," "Delivery Date," and "Occasion," allowing stakeholders to filter the entire                dashboard with a single click.
   
   Key Insights from the Dashboard

   ● High-Level Metrics: The business achieved ₹3,520,984 in Total Revenue from 1,000 orders, with an average customer spend of ₹3,520.98.

   ● Seasonal Drivers: Anniversary and Raksha Bandhan emerged as the top revenue-generating occasions.

   ● Product Performance: The "Colors" category is a significant revenue driver, followed closely by Soft Toys and Sweets.

   ● Geographic Reach: Cities like Dhanbad, Imphal, and Kavali show high order volumes, suggesting strong regional market penetration.

   ● Operational Efficiency: The average delivery time stands at 5.53 days, providing a benchmark for logistics performance.

Conclusion

Through the systematic application of ETL processes and data modeling, this dashboard transforms fragmented data into a strategic asset. It allows Ferns&Petals to make data-driven decisions regarding inventory management, marketing spend for specific occasions, and regional expansion.
