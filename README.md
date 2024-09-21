# DataCruxAnalytics

Welcome to **DataCruxAnalytics**—a comprehensive Excel dashboard designed to analyze and visualize sales data across different markets, regions, and product categories. This project is aimed at providing key insights into profitability, sales performance, and order priorities to help drive data-informed decisions.

## Overview

In this project, I utilized a dataset with various product sales, shipping costs, and order details, spanning multiple markets such as the US, APAC, EU, and Africa regions. The data includes categories like **Technology**, **Furniture**, and **Office Supplies**, further broken down into sub-categories (e.g., **Accessories**, **Phones**, **Chairs**).

### Key Metrics and Visualizations
The key metrics captured and analyzed in this dashboard include:
- **Sales**: Total sales values for each product.
- **Profit**: Net profit after deducting discounts and shipping costs.
- **Quantity Sold**: Number of items sold.
- **Discount**: Percentage of discount applied.
- **Order Priority**: Criticality of the order ranging from *Low* to *Critical*.

Using these metrics, I have created **7 key charts** focused on KPI analysis and breakdowns. These include:
1. **Segment Analysis**: Sales and performance segmented by category (Technology, Furniture, Office Supplies).
2. **Category Analysis**: A visual breakdown of sales, profit, and shipping costs by product category.
3. **Market Analysis**: Market-wise performance highlighting top-selling regions like US, APAC, and EU.
4. **Top 5 Products by Sales and Profit**: A comparison of the top 5 products based on their total sales and profitability.
5. **Bottom 5 Products by Sales and Profit**: Identifying underperforming products and regions with respect to sales and profit.
6. **World Map Visualization**: A geographical representation of the top 10 countries by sales.
7. **Market Share by Region**: A pie chart showing the overall market share of different regions, providing insights into the leading contributors.

### Advanced Features
- **Slicing and Dicing KPIs**: Interactive filters are applied to slice and dice important KPIs like **Sales**, **Profit**, **Discount**, and **Order Priority** across various dimensions such as **Market**, **Region**, and **Product Category**.
- **Top Sub-Category Contribution**: An analysis of the leading sub-categories and their contribution to overall sales. This chart highlights which sub-categories drive the most revenue.
- **World Map Visualization**: A detailed chart that visually represents the top 10 countries by sales, giving a global overview of market reach and performance.

### Future Enhancements
- Adding additional insights such as **sales forecasting** and **customer segmentation** to offer predictive analysis.
- Automating the data refresh using **Power Query** to ensure the dashboard reflects real-time updates.
- Exploring deeper trends with **regression analysis** and **correlation metrics**.

### Data Sample

| **Postal Code** | **Market** | **Region** | **Product ID**       | **Category**  | **Sub-Category** | **Product Name**                               | **Sales**  | **Quantity** | **Discount** | **Profit** | **Shipping Cost** | **Order Priority** |
|-----------------|------------|------------|----------------------|---------------|------------------|-------------------------------------------------|------------|--------------|--------------|------------|-------------------|--------------------|
| 10024           | US         | East       | TEC-AC-10003033       | Technology    | Accessories      | Plantronics CS510 - Over-the-Head Wireless Headset | 2309.65    | 7            | 0            | 762.18     | 933.57            | Critical            |
| APAC            | Oceania    | Oceania    | FUR-CH-10003950       | Furniture     | Chairs           | Novimex Executive Leather Armchair, Black         | 3709.39    | 9            | 0.1          | -288.76    | 923.63            | Critical            |
| APAC            | Oceania    | Oceania    | TEC-PH-10004664       | Technology    | Phones           | Nokia Smart Phone, with Caller ID                | 5175.17    | 9            | 0.1          | 919.97     | 915.49            | Medium              |
| EU              | Central    | Central    | TEC-PH-10004583       | Technology    | Phones           | Motorola Smart Phone, Cordless                   | 2892.51    | 5            | 0.1          | -96.54     | 910.16            | Medium              |
| Africa          | Africa     | Africa     | TEC-SHA-10000501      | Technology    | Copiers          | Sharp Wireless Fax, High-Speed                   | 2832.96    | 8            | 0            | 311.52     | 903.04            | Critical            |

---

## Conclusion

This dashboard, **DataCruxAnalytics**, offers a clear, interactive way to understand the key performance metrics (KPIs) driving sales and profitability across various markets. With visualizations that range from top-selling products to geographical insights, this project provides a solid foundation for making data-driven decisions in a business context. As an advanced beginner in data analytics, I am continuously expanding the dashboard with more advanced techniques, and I'm excited to see how it can help businesses optimize their performance.
