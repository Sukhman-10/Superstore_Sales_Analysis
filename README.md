🏬 Superstore Sales Data Analysis

This project presents an in-depth data analysis of Superstore Sales data, aimed at uncovering patterns in customer behavior, sales trends, and profit performance across multiple dimensions such as region, category, and gender.
It leverages statistical analysis, Tableau visualization, and clustering techniques to derive actionable business insights.

📁 Project Structure
Superstore-Sales-Analysis/
│
├── 📂 data/
│   ├── Superstore_Sales.csv        # Raw dataset
│   └── cleaned_data.csv            # Preprocessed dataset
│
├── 📂 notebooks/
│   ├── descriptive_analysis.ipynb  # Exploratory & statistical analysis
│   └── clustering_analysis.ipynb   # Cluster segmentation & insights
│
├── 📂 visualizations/
│   ├── sales_profit_per_state.png
│   ├── category_sales_boxplot.png
│   ├── gender_quantity_segment.png
│   ├── subcategory_sales_gender.png
│   └── treemap_category_state.png
│
├── 📜 report/
│   └── Superstore_Sales_Report.pdf  # Full analytical report (SPSS + Tableau)
│
├── 📄 README.md
└── 📄 requirements.txt

📊 Dataset Overview

The dataset consists of 250 customer records with 12 variables:

Variable	Description
Ship Mode	Type of delivery (First Class, Standard, Second Class, Same Day)
Customer Name	Name of the customer
Gender	Male / Female
Segment	Consumer, Corporate, or Home Office
State / Region	U.S. state and its corresponding region
Category / Sub-Category	Product category and its sub-classification
Sales	Sales amount (USD)
Quantity	Units sold
Discount	Discount applied (%)
Profit	Profit per order (USD)
⚙️ Tools & Technologies
Tool	Purpose
Tableau	Visualization and dashboard creation
SPSS	Statistical and T-Test analysis
Python (Pandas, NumPy, Matplotlib)	Data cleaning and clustering
Excel	Data preparation and verification
🔍 Analyses Performed
1. Descriptive Statistics

Computed mean, standard deviation, and variance for key measures.

Sales Mean: $275.12 | Profit Mean: $18.32

High variability in sales and profit distribution, with smaller deviations in quantity ordered.

2. Data Visualization
Quantity Purchased by Gender and Segment

Men tend to purchase more products in Consumer and Corporate segments. “Standard Class” shipping is the most preferred.

Sales and Profit per State

New York and California have the highest sales volumes, though California shows lower profit margins due to operational costs.

Sales by Product Category Across States

Technology leads in sales volume, followed by Office Supplies and Furniture. California and New York dominate across all categories.

Sub-Category Sales by Gender

Men buy more paper (highly profitable), while women prefer binders. Profitability varies across sub-categories.

Category-Wise Sales Distribution

Technology shows the largest spread in revenue and dominates average sales values.

3. T-Test Analysis

Compared Sales and Discounts across genders.

Result: No significant statistical difference (p > 0.05).

Indicates similar spending patterns between male and female customers.

4. Factor Analysis (PCA)

Variables: Sales, Category, Gender, Discount, Segment

First two components explained ~46% variance.

Sales and Category are the most influential features.

Suggests moderate correlation; PCA reveals primary patterns of variation.

5. Cluster Analysis
Cluster	Characteristics	Interpretation
1	High sales, high profit	Premium transactions
2	Average sales & profit	Regular transactions
3	Low sales, moderate profit	Small-scale customers
4	High sales, negative profit	Loss-making operations

Clusters reveal business opportunities: focus on Cluster 1 for growth, investigate Cluster 4 for cost reduction.

📈 Key Insights

Technology category drives most revenue and profit.

Standard shipping is the dominant, cost-effective mode.

Regional performance shows uneven profit distribution.

No gender-based performance difference.

Clustering helps segment customers by profitability and operational characteristics.

🧠 Business Recommendations

Focus on Technology category and optimize Standard Class logistics.

Investigate loss clusters to reduce operational inefficiencies.

Strengthen marketing in high-sales, low-profit regions.

Introduce targeted promotions by sub-category and customer type.

🚀 Future Enhancements

Integrate predictive models (e.g., regression, classification) for sales forecasting.

Expand dataset to improve PCA and clustering robustness.

Develop a Tableau or Power BI dashboard for real-time business insights.

👤 Author

Author: [Your Name]
Tools: Tableau | SPSS | Excel | Python
Purpose: Academic / Business Analytics Research

🪪 License

This project is licensed under the MIT License — feel free to use, modify, and distribute with proper attribution.
