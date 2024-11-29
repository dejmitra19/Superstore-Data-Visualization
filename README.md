# Saving Superstore: A Data Visualization Project

## Project Overview
The superstore is facing financial challenges, and this project aims to identify areas of profit and loss, evaluate advertising strategies, and analyze return rates to provide actionable recommendations to increase profitability and avoid bankruptcy. Using Tableau and Excel, I created visualizations to justify conclusions for each business-critical question.

## Objectives
1. **Profits & Losses**:
   - Identify key profit and loss centers.
   - Determine which products and subcategories to focus on or discontinue.
2. **Advertising**:
   - Analyze the return on ad spend across states and months to recommend advertising strategies.
3. **Returned Items**:
   - Investigate return rates by product and customer, and their impact on profitability.

## Tools and Techniques
- **Datasets**: `Superstore.xls`
- **Tableau**: For creating dynamic dashboards and visualizations.
- **Data Preparation**:
  - Left join the `Returns` table onto the `Orders` table to analyze return rates.
  - Calculate custom fields for return rates and profitability analysis.

## Key Insights
### 1. Profits & Losses
- **Top Profit Centers**:
  - **Subcategory + Region**: Technology in the South and Central regions generated the highest profits.
  - **Shipping Mode + Product**: Standard Class shipping and high-value products were the most profitable combinations.
- **Biggest Loss Makers**:
  - **Product Name**: The **GBC DocuBind P400 Electric Binding System** had a loss of -$20,585.
  - **Subcategory + Region**: Tables in the South and Bookcases in the West regions generated consistent losses.
- **Subcategories to Focus On**:
  - Chairs, Phones, and Accessories were identified as key profit drivers.
- **Subcategories to Discontinue**:
  - Tables, Bookcases, and Supplies.

### 2. Advertising
- **Best States and Months**:
  - Virginia, Indiana, and Rhode Island showed the highest average profits during specific months.
  - For example, Virginia in February achieved a profit of $199.5, while Indiana peaked at $79.1 in May.
- **Recommended Budget**:
  - Allocate 1/5 of profits for advertising in the top-performing states and months. For example, spending ~$40 for a potential $200 profit in Virginia is justified.

### 3. Returned Items
- **Products with the Highest Return Rates**:
  - The **Apple iPhone 5** and **Global Troy Executive Leather Task Chair** had the highest return rates.
- **Customers with the Highest Return Rates**:
  - Seth Vernon and William Brown had higher-than-average return rates.
- **Profit vs. Return Rate**:
  - States with higher return rates, such as Rhode Island, had lower profitability, suggesting the need for stricter return policies for specific regions or products.

## Visualizations
The Tableau dashboard includes:
1. **Profit and Loss Centers**:
   - Subcategory and region analysis to identify profitable and loss-making combinations.
2. **Advertising ROI Analysis**:
   - Monthly profit trends across states to pinpoint optimal advertising opportunities.
3. **Return Rate and Profitability**:
   - Scatterplot showing the relationship between return rates and profits for dimensions like state and shipping mode.

## Files Included
- [Saving Superstore Insights Tableau Dashboard](https://public.tableau.com/views/Book2_17329210557970/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link): Tableau Public dashboard.
- `Saving_Superstore_Insights.twbx`: Tableau workbook with analysis.
- `Superstore.xls`: Dataset used for the project.

## How to Use
1. View the published dashboard on [Tableau Public](https://public.tableau.com/views/Book2_17329210557970/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).
2. Explore the Tableau workbook (`Saving_Superstore_Insights.twbx`) for detailed visualizations.
3. Refer to the `Superstore.xls` file for raw data analysis.

## Future Improvements
- Automate data updates in Tableau for real-time insights.
- Explore advanced predictive modeling for customer and product profitability.

---

## Submission Instructions
This repository contains all files necessary for the project review:
- `README.md`
- Tableau workbook: `Saving_Superstore_Insights.twbx`
- Dataset: `Superstore.xls`

---

## Contact
If you have any questions or need further details, feel free to reach out!
