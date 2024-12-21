# E-commerce Order & Supply Chain Analysis

## **Executive Summary**
This analysis provides key business insights to guide decision-making in revenue generation, product strategy, and operational efficiency for **Mercado**. With a total revenue of **$29.92M**, the data highlights significant contributions from categories like **Toys** (**73.5%** of total revenue) and regions such as **São Paulo** (**42%** of total revenue). The analysis also identifies underperforming categories, such as Fashion Female Clothing and Diapers & Hygiene, suggesting opportunities for strategic adjustments. Operationally, the shipping team has achieved an impressive **93.59% on-time delivery rate**, with an average delivery time outperforming estimates by **13 days**. However, **51%** of delivery delays are concentrated in **São Paulo** and **Rio de Janeiro**, highlighting areas for improvement in logistics. Actionable recommendations include category-specific promotional strategies, location-based marketing, and targeted logistical improvements to enhance customer satisfaction and business profitability.

---

## **Dataset Overview**
The dataset consists of multiple tables providing information about orders, order items, customers, payments, and products. Key attributes include:
- **Orders**: Order status, timestamps, and delivery details.
- **Order Items**: Products purchased, prices, and shipping charges.
- **Customers**: Location and demographic information.
- **Payments**: Payment types, values, and installments.
- **Products**: Product categories, dimensions, and weights.

![alt text](image-18.png)
---

## Skills Used

- **Power BI**: Data visualization and insights generation.
- **Excel**: Basic analysis and handling of data.
- **Power Query**: Data cleaning and transformation.


## **Data Cleaning**
Performed in Power Query:

- Removed duplicates from tables with primary key columns.
- Replaced null values in product categories with 'unidentified.'
- Created a calendar table for better date handling.
- Separated columns with date and timestamp into individual fields.
- Added helper columns to calculate differences between actual and estimated delivery dates.
Delivery Status Column's logic is as below:


 <img src = "image-16.png" width="900" height="500">  

## **Assumptions**
Only orders with a "delivered" status were considered for this analysis.

## Key Insights

### 1. Sales and Revenue

- **Total Revenue**: *$29.92M*

#### High-Performing Categories

- **Toys**: *Revenue $22M, Orders 67,027, AOV $343.07*
  - High sales volume and lower AOV suggest frequent, smaller purchases. Opportunity: Expand product offerings and focus on promotional activities during peak seasons.
- **Furniture & Décor**: *Revenue $739K, Orders 1,760, AOV $427.88*
  - Healthy order volume and AOV indicate a potential customer base focused on home improvement. Opportunity: Target seasonal promotions and unique designs.
- **Garden Tools**: *Revenue $732K, Orders 807, AOV $925.14*
  - High AOV indicates significant spending on individual purchases. Opportunity: Seasonal promotions or bundling strategies could increase sales.

#### Underperforming Categories

- **Fashion Female Clothing**: *Revenue $68, Orders 2, AOV $34.07*
  - Poor market penetration and low AOV suggest potential marketing or product quality issues.
- **Diapers & Hygiene**: *Revenue $126.46, Orders 1, AOV $18.42*
  - Low visibility or demand suggests a need for better marketing strategies or evaluation of product relevance.


### **2. Location Insights**
- Customers from São Paulo contributed **42%** of total revenue, highlighting this state as a key market.
- Order density is concentrated on the east coast of South America, especially in and around São Paulo and Rio de Janeiro.

   #### Potential Growth Area

   Minas Gerais (MG) state shows potential as high-volume order region, ranking 3rd but have sales volumes 3 times less than São Paulo and Rio de Janeiro. This state could benefit from targeted marketing campaigns to close the gap.

### 3. Shipping Performance

- **On-Time Delivery Rate**: **93.59%** of orders were delivered on or before the estimated date.
- **Delivery Efficiency**: Actual average delivery time is **12 days**, significantly outperforming the **estimated 25 days**.
- **Delayed Orders**: 51% of delays occurred in São Paulo and Rio de Janeiro, requiring further investigation into logistics in these regions.


### **4. Payment Trends**
- **Top Payment Type**: Around **74%** of the total orders were paid by credit card.
- **Installments**: **61%** of the orders are paid within 0–2 installments, indicating that a majority of customers prefer to pay upfront or split payments over a short duration. Higher upfront payments means more liquidity revenue realization will be quicker for the business.



## Recommendations

1. **Revenue Optimization**:

   - Focus on promoting high-performing categories like Toys and Garden Tools during peak seasons.
   - Reevaluate and revamp strategies for underperforming categories, such as Fashion Female Clothing and Diapers & Hygiene.
   - Introduce targeted discounts, loyalty programs, or cross-category bundles to boost sales across various customer demographics.

2. **Location-Specific Marketing**:

   - Double down on marketing efforts in São Paulo and Rio de Janeiro, which generate the majority of revenue.
   - Target high-potential states like Minas Gerais (MG), ranking 3rd in terms of volume, to bridge the revenue gap.

3. **Shipping and Logistics Improvements**:

   - Investigate and address logistical challenges causing delivery delays in São Paulo and Rio de Janeiro.
   - Maintain high on-time delivery performance and leverage it as a competitive advantage in customer communications.

---

## Next Steps/Future Scope

1. **Enhanced Analysis**:

   - Include customer segmentation analysis to identify high-value customers.
   - Analyze repeat purchase behavior and customer lifetime value.

2. **Data Enrichment**:

   - Integrate additional data points such as marketing campaigns and seasonal trends for deeper insights.

3. **Predictive Modeling**:

   - Build predictive models to forecast sales and anticipate logistical(with more logistics related data points) challenges.
   - Use machine learning to recommend personalized products to customers.

4. **Visualization Improvements**:

   - Create more interactive dashboards to allow stakeholders to explore insights dynamically.

---

## **Usage Instructions**
1. Clone the repository: `git clone <repo-url>`
2. Open the Power BI dashboard file (`dashboard.pbix`) to explore visuals and insights.

---


**Author**: Gautami Shinde
