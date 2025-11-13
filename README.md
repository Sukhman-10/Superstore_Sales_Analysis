🏬 Superstore Sales Data Analysis

This project presents an in-depth data analysis of a Superstore Sales dataset, focusing on understanding customer behavior, sales performance, profit margins, and key business insights through statistical and visual analysis.

📊 Project Overview

The dataset used in this project contains 250 customer records with 12 key variables describing sales transactions across different U.S. states and regions. The analysis explores patterns, relationships, and clusters to derive actionable business insights.

📁 Dataset Information

Columns in the dataset:

Ship Mode: Delivery type (First Class, Standard Class, Second Class, Same Day)

Customer Name: Name of the customer

Gender: Male/Female

Segment: Market type (Consumer, Corporate, Home Office)

State & Region: U.S. state and geographical region (West, East, Central, South)

Category / Sub-Category: Product category and its sub-classification

Sales: Sales value in USD

Quantity: Units ordered

Discount: Discount applied (%)

Profit: Profit generated per order

⚙️ Tools & Technologies Used

Python / SPSS: For descriptive statistics and inferential analysis

Tableau: For interactive data visualization

Excel: For data preparation and validation

🔍 Key Analyses Performed
1. Descriptive Statistics

Calculated mean, median, standard deviation, and variance for key metrics (Sales, Profit, Quantity).

Identified substantial variation in sales and profits.

Observed that Standard Class is the most common shipping mode and male customers generally contribute more sales.

2. Data Visualization

Sales & Profit per State: Revealed geographical disparities (e.g., California high sales but low profits).

Category-wise & Subcategory-wise Analysis: Highlighted Technology as a high-performing category.

Gender-based Purchases: Males purchase more paper, females prefer binders; possible marketing implications.

Box Plots & Tree Maps: Illustrated distribution of revenue and sales concentration by category/state.

3. T-Test Analysis

Compared Sales and Discounts between genders.

Found no significant statistical difference (p > 0.05) between male and female sales patterns.

Suggested that sales differences could be due to chance rather than gender-based trends.

4. Factor Analysis (PCA)

Analyzed five key variables: Sales, Category, Gender, Discount, Segment.

Found moderate correlation but low KMO score, suggesting limited suitability for factor analysis.

Identified Sales and Category as dominant components influencing variance.

5. Cluster Analysis

Applied clustering on Sales, Profit, Ship Mode, Segment, Category, Region.

Formed 4 clusters showing distinct transaction patterns:

Cluster 1: Highly profitable transactions

Cluster 4: Loss-making transactions

Cluster 2 & 3: Average, common transactions

Highlighted potential business actions—reduce losses in Cluster 4, focus growth on Cluster 1.

📈 Key Insights

High variability in sales and profit across regions and customers.

Technology category dominates sales and profit share.

Standard shipping is the most popular and cost-effective mode.

No major gender bias in overall sales performance.

Cluster-based segmentation helps identify profitable and non-performing customer groups.

🧠 Business Implications

Focus marketing efforts on Technology products and Standard Class shipping promotions.

Address loss clusters by revisiting pricing or operational costs.

Leverage regional insights (e.g., high sales but low profit areas) to optimize strategy.

Use PCA-driven variable selection for targeted predictive modeling in future work.

📌 Future Scope

Incorporate predictive modeling for profit forecasting.

Enhance data volume for more robust factor and cluster analysis.

Build a dashboard integrating Tableau visuals for real-time decision-making.

📄 Author

Author: [Your Name]
Tools Used: Tableau, SPSS, Excel
Purpose: Academic/Business Analytics Research

🪪 License

This project is released under the MIT License – feel free to use, modify, and share with attribution.
