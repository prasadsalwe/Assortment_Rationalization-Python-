📌 Project Objective

To optimize the grocery product assortment by identifying underperforming items, highlighting high-demand and high-margin products, and recommending a rationalization strategy that improves profitability, reduces working capital, and enhances customer satisfaction.

📂 Dataset Used

The dataset contains 4,996 product records across key attributes including:

Product_ID

Category

Product_Name

Brand

Price & Cost

Units Sold

Shelf Space

Customer Ratings

Frequency of Purchase

Sales & Gross Margin

Customer Count & Transactions

Derived KPIs (Sales per Customer, Shelf Space KPIs, Rating Proxy, Performance Score)

❓ Business Questions / KPIs Addressed

Sales & Margin Metrics

Identify top and bottom performers by sales and gross margin.

Customer Demand Analysis

Ratings, purchase frequency, and customer proxy (Rating × Frequency).

Shelf Space Efficiency

Units sold per shelf space

Sales per shelf space

Margin per shelf space

Product Profitability

Gross margin %, profit per unit, negative margin products.

Performance Score

A composite normalized metric combining all key KPIs.

Assortment Decisions

Which products to retain, optimize, or eliminate.

🔄 Process Followed
1. Data Familiarization

Loaded dataset using files.upload

Understood column structure and data types

2. Data Cleaning

Fixed null values

Removed duplicates

Corrected inconsistent categories/brands

3. Feature Engineering

Created actionable KPIs:

Sales per Customer

Sales per Shelf Space

Gross Margin per Shelf Space

Units Sold per Shelf Space

Profit per Shelf Space

Customer Rating Proxy

Gross Margin per Unit Sold

4. Feature Normalization

Min–max scaled all KPIs

Combined them into a Final Performance Score

5. Segmentation by Percentiles

75th percentile → Top Performers

25–75 percentile → Medium Performers

<25th percentile → Under Performers

6. Visualization & Analysis

Category-wise and brand-wise sales charts

Correlation analysis

Shelf-space efficiency plots

Performance score distribution

7. Recommendations

Expansion, optimization, and elimination strategies based on performance score.

📊 Project Insights

Top performers occupy only 19% of shelf space but contribute 34% of performance → highly efficient items.

Medium performers consume 54% space but contribute only 48% performance → potential for optimization.

Under performers waste 28% shelf space while generating only 17% performance → major reduction opportunity.

Customer rating correlation with frequency and sales was near zero, indicating customers buy out of necessity, not preference.

Several items priced below cost were identified → margin leakage.

Shelf space KPIs highlighted many slow-moving, low-margin items consuming high space.

🏁 Final Conclusion

The analysis shows that a targeted assortment rationalization strategy can free up significant shelf space, reduce inventory inefficiencies, and improve profitability. By eliminating low-performing SKUs and reallocating space toward high-demand, high-margin products, the retailer can achieve:

Higher sales per square meter

Improved customer satisfaction

Reduced working capital

A more streamlined and profitable assortment

This project demonstrates a complete data-driven assortment optimization framework that can be reused across multiple retail categories.
