# DataCruxAnalytics

Welcome to **DataCruxAnalytics**—a comprehensive Excel dashboard designed to analyze and visualize sales data across different markets, regions, and product categories. This project is aimed at providing key insights into profitability, sales performance, and order priorities to help drive data-informed decisions.

## Overview

In this project, I utilized a dataset with various product sales, shipping costs, and order details, spanning across multiple markets such as the US, APAC, and EU regions. The data includes categories like **Technology**, **Furniture**, and **Office Supplies**, further broken down into sub-categories (e.g., **Accessories**, **Phones**, **Chairs**).

The key metrics captured and analyzed in this dashboard include:
- **Sales**: Total sales values for each product.
- **Profit**: Net profit after deducting discounts and shipping costs.
- **Quantity Sold**: Number of items sold.
- **Discount**: Percentage of discount applied.
- **Order Priority**: Criticality of the order ranging from *Low* to *Critical*.
  
## Key Features

1. **Profitability Analysis**: Track the profit margins by comparing sales and profit for each product, identifying the most profitable items and regions.
2. **Sales Performance**: Analyze the total sales across different markets (US, APAC, EU, Africa) and regions, identifying trends and areas for growth.
3. **Order Priority & Shipping Costs**: Visualize how shipping costs impact profitability and evaluate the priority of orders to ensure efficient inventory management.
4. **Dynamic Filters**: Use slicers to filter the data based on market, region, category, and order priority for more in-depth analysis.

## Data Used

| **Postal Code** | **Market** | **Region** | **Product ID**       | **Category**  | **Sub-Category** | **Product Name**                               | **Sales**  | **Quantity** | **Discount** | **Profit** | **Shipping Cost** | **Order Priority** |
|-----------------|------------|------------|----------------------|---------------|------------------|-------------------------------------------------|------------|--------------|--------------|------------|-------------------|--------------------|
| 10024           | US         | East       | TEC-AC-10003033       | Technology    | Accessories      | Plantronics CS510 - Over-the-Head Wireless Headset | 2309.65    | 7            | 0            | 762.18     | 933.57            | Critical            |
| APAC            | Oceania    | Oceania    | FUR-CH-10003950       | Furniture     | Chairs           | Novimex Executive Leather Armchair, Black         | 3709.39    | 9            | 0.1          | -288.76    | 923.63            | Critical            |
| APAC            | Oceania    | Oceania    | TEC-PH-10004664       | Technology    | Phones           | Nokia Smart Phone, with Caller ID                | 5175.17    | 9            | 0.1          | 919.97     | 915.49            | Medium              |
| EU              | Central    | Central    | TEC-PH-10004583       | Technology    | Phones           | Motorola Smart Phone, Cordless                   | 2892.51    | 5            | 0.1          | -96.54     | 910.16            | Medium              |
| Africa          | Africa     | Africa     | TEC-SHA-10000501      | Technology    | Copiers          | Sharp Wireless Fax, High-Speed                   | 2832.96    | 8            | 0            | 311.52     | 903.04            | Critical            |

## Skills Demonstrated
- **Data Cleaning**: Handling missing data and correcting inconsistencies to prepare the dataset for analysis.
- **Formulas and Functions**: Leveraging Excel functions like `XLOOKUP`, `SUMIF`, and `IFERROR` to enhance analysis.
- **Pivot Tables and Charts**: Creating interactive pivot tables and charts to visualize sales, profit, and order data.
- **Conditional Formatting**: Highlighting key metrics such as high-profit items, discounted orders, and low-sales products for better decision-making.
- **Dashboard Design**: Structuring the dashboard with slicers, graphs, and KPIs to allow users to slice and dice the data dynamically.

## Future Enhancements
- Incorporating more advanced metrics like customer segmentation and sales forecasting.
- Automating data updates using Power Query to maintain real-time analysis.
- Adding deeper insights into market trends through regression analysis and visual storytelling.
- 
