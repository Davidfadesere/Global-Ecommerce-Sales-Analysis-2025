# Global E-Commerce Sales Analysis 🌍📊
<img width="926" height="520" alt="1000824811" src="https://github.com/user-attachments/assets/a39ecc25-4e56-4964-9091-4263a95ae3d1" />

<img width="920" height="526" alt="1000824815" src="https://github.com/user-attachments/assets/61b50c27-1fde-41d2-a844-d94ecb5a75fe" />


## Project Overview

This project involves a comprehensive analysis of global e-commerce transactions to identify key drivers of revenue, regional performance trends, and consumer category preferences. By transforming raw transactional data into an interactive dashboard, I provided actionable insights that can guide inventory management and targeted marketing strategies.

## Problem Statement

A global retail entity needed to understand its performance across 10 different countries and 8 product categories. The raw data was siloed in spreadsheets, making it difficult to identify:

* Which regions contribute most to the bottom line.
* Which product categories are trending or underperforming.
* Seasonal sales patterns that impact supply chain planning.

## Tech Stack & Tools

* **Excel:** Initial data exploration and structural validation.
* **Power Query:** Data cleaning, handling nulls, and transforming date/currency formats.
* **DAX (Data Analysis Expressions):** Created custom measures for KPIs including Total Revenue, Quantity Sold, and Average Order Value (AOV).
* **Power BI:** Developed an interactive, multi-page dashboard for visual storytelling.

## Data Transformation Process

1. **Extraction:** Imported a dataset of 1,200 unique transactions.
2. **Cleaning:** Used Power Query to ensure data integrity, specifically standardizing the `Order_Date` field and validating the `Total_Amount` calculation (Unit Price × Quantity).
3. **Modeling:** Built a star-schema-ready flat table for optimized performance within Power BI.
4. **Calculations:** Authored DAX measures:
* `Total Revenue = SUM(Sales[Total_Amount])`
* `Average Order Value = AVERAGE(Sales[Total_Amount])`



## Key Insights & Findings

* **Revenue Performance:** The store generated a total of **$1.51 Million** in revenue.
* **Geographic Leaders:** The **USA ($206K)** and **UAE ($185K)** are the highest-performing markets, indicating strong brand presence in these regions.
* **Category Dominance:** Contrary to expectations, **Home Decor** emerged as the top category (**$232K**), followed by Grocery and Electronics.
* **Seasonal Trends:** Analysis revealed a significant performance peak in **July 2025 ($180K)**, suggesting a highly successful mid-year promotion or seasonal demand spike.

## How to Use This Repository

1. **Data:** The raw `.csv` file is located in the `data/` folder.
2. **Report:** Open the `.pbix` file to interact with the dashboard.

## Conclusion

This analysis proves that while the company has a broad global reach, focus should be intensified on the Home Decor category in the North American and Middle Eastern markets to maximize ROI.
