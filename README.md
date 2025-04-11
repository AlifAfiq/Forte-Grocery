# Forte-Grocery


This project delivers a Power BI dashboard for Forte Grocery, analyzing sales, profit, stock levels, and supplier performance. It helps identify top-performing categories, low-stock items, and efficient suppliers. The insights support better inventory planning, cost control, and strategic decision-making across procurement, sales, and supply chain operations.

# 1. Introduction
This document outlines the requirements for an inventory analysis system to improve decision-making in stock management, supplier performance, and sales tracking.

## 1.1 Purpose
The purpose of this document is to define the key metrics and visualization requirements needed to analyze the grocery inventory efficiently.

## 1.2 Scope
The system should track sales trends, inventory levels, supplier performance, and profitability. The insights should be presented through key performance indicators (KPIs) and visualizations.

## 1.3 Problems
Effective inventory management is crucial for business success, yet companies face several challenges that can significantly impact operations and profitability.

### - Lack of Profitability Insights: 

Users struggle to determine which product categories generate the most profit and sales. Without visibility into profitability, businesses may allocate resources inefficiently, focusing on low-margin products instead of high-profit items. 

This lack of insight can lead to poor pricing strategies, ineffective marketing efforts, and ultimately, reduced revenue and profit margins.

Users wish to know the most profitable and sold category. They also need to know whether the sales volume contributes to the profit and the significant impact of average unit price of the category towards the profit.

### - Stock Level Uncertainty and Overstocking Risks: 

Inventory managers often lack real-time data on stock levels, reorder quantities, and associated costs. 

If stock levels are not monitored effectively, businesses may run out of popular items, leading to lost sales and dissatisfied customers. 

On the other hand, over-ordering can tie up capital in unsold stock, increase storage costs, and lead to wastage, especially for perishable goods.

The users wish to know if they are keeping up with the reorder thresholds or not.



### - Inconsistent Supplier Performance and Delivery Delays: 

Businesses frequently encounter challenges in tracking supplier reliability. If suppliers take too long to fulfill orders, it can result in stock shortages and disruptions in business operations. 

Additionally, relying on suppliers with unpredictable delivery times makes it difficult to plan inventory effectively, potentially leading to unmet customer demand, loss of market reputation, and increased operational costs.

The users need to know which suppliers can deliver much items in short period.

## 1.4 Solutions
To address these challenges, the system should incorporate a data-driven approach using key metrics and visualizations that provide actionable insights:

### - Sales and Profitability Analysis: 

The dashboard should display total sales and profit per category, along with their respective percentages. 

This allows businesses to identify the most profitable product segments and understand whether a category’s profitability is driven by high sales volume or higher pricing. 

Having this information enables businesses to optimize pricing strategies, focus marketing efforts on high-margin products, and adjust inventory purchases accordingly.


### - Stock Levels and Reorder Alerts:

The system should present current stock levels and reorder quantities to help inventory managers maintain optimal stock levels. 

By providing clear visibility into which products are low in stock and require replenishment, businesses can prevent stockouts and overstocking, minimize holding costs, and streamline the supply chain process. 

Additionally, tracking the total reorder cost will help financial planning by forecasting future expenditures.

### - Supplier Performance Analysis: 
The system should evaluate supplier efficiency based on average delivery time (days) between order placement and stock arrival. 

This metric allows businesses to assess which suppliers deliver consistently on time and which ones are causing delays that could impact sales and customer satisfaction.

By integrating this data, companies can negotiate better contracts with reliable suppliers, reduce lead times, and improve operational efficiency.

# 2. Functional Requirements
The inventory analysis system should generate insights using the following KPIs and charts:

Total Profit and Sales Volume: Display the total profit and sales volume contributed by all items across categories.

- Top-profitable Products: List the highest profit contribution products.

- Stock Levels & Reorder Alerts: Indicate which products require replenishment.

- Profit Estimation by Category: Display profit per category along with percentage representation using a donut chart.

-Sales Volume by Category: Display sales volume per category along with percentage representation using a donut chart.

- Average Price per Category: Identify the average pricing trends for different product groups.

- Reorder Unit Needed and Cost: Calculate the reorder quantity and its cost based on current stock levels.

- Supplier Performance on Average Delivery Time: Measure the efficiency of suppliers by calculating the average number of days taken to deliver stock from the order date.

# 3. Non-Functional Requirements
- The system should support efficient data visualization tools such as Power BI or Tableau.
- Queries should be optimized for quick data retrieval.
- Data accuracy should be maintained through validation and regular updates.

# 4. Expected Outcomes and Business Impact

The implementation of this inventory analysis dashboard will provide valuable insights and lead to informed decision-making across various business functions:

## - Sales Department Benefits: 

With access to sales and profit analysis, the sales team can identify which product categories contribute the most to revenue. 

They can also determine whether profitability is driven by high sales volume or premium pricing. 

This insight allows them to develop better pricing strategies, adjust promotional efforts, and focus on selling high-margin products to maximize revenue.


## - Inventory and Stock Management: 

Inventory managers will gain real-time visibility into stock levels, allowing them to plan reorders effectively and avoid stockouts or overstocking. 

By analyzing reorder costs and supplier performance, they can also optimize supplier selection, choosing vendors that offer faster delivery times and lower costs, ensuring a smooth supply chain process.

## - Supplier Relationship and Performance Tracking: 

Businesses will have a clear evaluation of supplier reliability based on delivery time performance. 
This information helps procurement teams negotiate contracts with suppliers that offer timely deliveries and consistent stock availability. Companies can also diversify their supplier base to reduce risks associated with delayed deliveries.

## - Financial Planning and Cost Optimization: 

With insights into inventory value, reorder costs, and supplier efficiency, finance teams can improve budget planning and optimize cash flow management. 

Having a clear forecast of inventory expenses ensures that capital is allocated efficiently, reducing unnecessary stock purchases and holding costs.

By leveraging this dashboard, businesses can make data-driven decisions, improve operational efficiency, and enhance overall profitability.


# 5. Action

## 1: Promote High-Margin Categories like Beverages

The dashboard reveals that Beverages rank second in profit (20%) despite having the lowest sales volume, likely due to their high average unit price (3x Fruits & Vegetables). This indicates an opportunity to maximize profit by promoting premium-priced products rather than only focusing on top-sellers.

To capitalize on this, businesses should launch targeted marketing campaigns for Beverages, emphasizing quality and value to justify the price. Strategies like product bundling, loyalty offers, and upselling premium beverages with everyday items can increase transaction value. Additionally, refining pricing strategies through A/B testing may further enhance margins without sacrificing demand.

Rather than allocating all marketing spend to high-volume categories, the focus should shift to high-profit ones with growth potential. This balanced strategy ensures profit optimization, better resource allocation, and stronger brand positioning across both mass and premium segments.

By identifying and actively promoting categories with strong profit-to-volume ratios, businesses can boost overall profitability without needing a significant increase in units sold, a more efficient and sustainable growth path.

## 2: Replenish Low-Stock Items and Implement Dynamic Reorder System

The dashboard highlights a major risk: current stock for items marked for reorder is only at 50% of the desired level. This suggests that key products are close to stockout, which can result in lost sales, dissatisfied customers, and operational disruption.

To address this, businesses should immediately restock items below reorder thresholds. Simultaneously, they should adopt a dynamic reorder model that adjusts reorder points based on real-time sales velocity, seasonality, and supplier delivery times. This moves inventory management from static rules to data-driven decision-making.

Setting up automated reorder alerts and forecasting demand based on trends will help prevent under- or over-stocking. Also, integrating reorder costs into financial planning ensures smarter cash flow management, especially for perishable items with higher holding risks.

By doing this, the company can improve inventory turnover, maintain customer satisfaction, and reduce waste and carrying costs. A responsive inventory system not only minimizes risks but also supports long-term operational efficiency and supply chain resilience.


## 3: Prioritize High-Performing Suppliers with Faster Delivery

Supplier analysis shows that several vendors  such as Rhynoodle, Mydo, and Skivee consistently deliver over 80 units in under 60 days, with Rhynoodle being the most efficient at 33 days. This performance data is critical for supply chain optimization.

To improve supplier management, businesses should create a Preferred Supplier Program, giving high-performing vendors more consistent orders in exchange for maintaining fast, reliable delivery. This encourages suppliers to uphold or improve service levels. At the same time, underperforming suppliers should undergo performance reviews or renegotiation of terms.

By strategically favoring suppliers who deliver both speed and volume, businesses enhance their operational agility and customer satisfaction, while also reducing storage and delay costs. Long-term, this builds a resilient supplier network, critical for maintaining competitive advantage and consistent product availability.


# 6. Conclusion

Implementing this inventory analysis system will help businesses make strategic and well-informed decisions regarding sales strategies, stock management, supplier selection, and financial planning. It ensures operational efficiency, reduces risks associated with stock shortages and overstocking, and enhances overall profitability through data-driven insights.






Reference


Convertcart. “10 Product Bundling Examples That Convert (& 10 Proven Ideas) | ConvertCart.” Www.convertcart.com, 7 Feb. 2025, www.convertcart.com/blog/product-bundling-examples.
Michael. “How to Automate Reordering Processes in Inventory Management: Strategies, Benefits, and Best Practices. - Versa Cloud ERP - Blog.” Versa Cloud ERP - Blog, 11 Oct. 2024, www.versaclouderp.com/blog/how-to-automate-reordering-processes-in-inventory-management-strategies-benefits-and-best-practices/.
Team, Vendorful. “Preferred Supplier Program: What It Is and How to Implement.” Vendorful - Supplier Relationship Management and E-Sourcing, 18 Feb. 2023, vendorful.com/preferred-supplier-program-what-it-is/. Accessed 11 Apr. 2025.
