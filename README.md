# 🏬 Superstore Sales Data Analysis

This project presents an in-depth analysis of Superstore Sales data, uncovering patterns in customer behavior, sales trends, and profit performance across multiple dimensions such as region, category, and gender. It leverages statistical analysis, Tableau visualization, and clustering techniques to derive actionable business insights.

## 📊 Dataset Overview

The dataset consists of 250 customer records with 12 variables:

| Variable           | Description                                      |
|-------------------|--------------------------------------------------|
| Ship Mode          | Type of delivery (First Class, Standard, Second Class, Same Day) |
| Customer Name      | Name of the customer                             |
| Gender             | Male / Female                                   |
| Segment            | Consumer, Corporate, or Home Office             |
| State / Region     | U.S. state and its corresponding region         |
| Category / Sub-Category | Product category and sub-classification   |
| Sales              | Sales amount (USD)                               |
| Quantity           | Units sold                                       |
| Discount           | Discount applied (%)                             |
| Profit             | Profit per order (USD)                           |

---

## ⚙️ Tools & Technologies

| Tool      | Purpose                                      |
|-----------|---------------------------------------------|
| Tableau   | Visualization and dashboard creation        |
| SPSS      | Statistical and T-Test analysis             |
| Python (Pandas, NumPy, Matplotlib) | Data cleaning and clustering |
| Excel     | Data preparation and verification           |

---

## 🔍 Analyses Performed

### 1. Descriptive Statistics
- Computed mean, standard deviation, and variance for key measures.
- **Sales Mean:** $275.12 | **Profit Mean:** $18.32
- Observed high variability in sales and profit, moderate deviations in quantity.

### 2. Data Visualization
- **Quantity Purchased by Gender and Segment**  
  ![Gender vs Quantity]

- **Sales and Profit per State**  
  ![Sales Profit per State]

- **Sales by Product Category Across States**  
  ![Category Sales Boxplot]

- **Sub-Category Sales by Gender**  
  ![Subcategory Sales Gender]

- **Category-Wise Sales Distribution (Treemap)**  
  ![Treemap Category State]

### 3. T-Test Analysis
- Compared Sales and Discounts across genders.  
- **Result:** No significant statistical difference (p > 0.05).  
- Interpretation: Similar spending patterns between male and female customers.

### 4. Factor Analysis (PCA)
- Variables: Sales, Category, Gender, Discount, Segment
- First two components explained ~46% of variance.
- Sales and Category are most influential features.

### 5. Cluster Analysis

| Cluster | Characteristics             | Interpretation               |
|---------|-----------------------------|------------------------------|
| 1       | High sales, high profit      | Premium transactions         |
| 2       | Average sales & profit       | Regular transactions         |
| 3       | Low sales, moderate profit   | Small-scale customers        |
| 4       | High sales, negative profit  | Loss-making operations       |

- Clusters reveal opportunities: focus on Cluster 1 for growth, investigate Cluster 4 for cost reduction.

---

## 📈 Key Insights
- Technology category drives most revenue and profit.
- Standard shipping is the dominant, cost-effective mode.
- Regional performance shows uneven profit distribution.
- No gender-based performance difference.
- Clustering helps segment customers by profitability and operational characteristics.

---

## 🧠 Business Recommendations
- Focus on Technology category and optimize Standard Class logistics.
- Investigate loss clusters to reduce operational inefficiencies.
- Strengthen marketing in high-sales, low-profit regions.
- Introduce targeted promotions by sub-category and customer type.

---

## 🚀 Future Enhancements
- Integrate predictive models (regression/classification) for sales forecasting.
- Expand dataset to improve PCA and clustering robustness.
- Develop a Tableau or Power BI dashboard for real-time insights.

---

## 👤 Author
**Author:** [Your Name]  
**Tools:** Tableau | SPSS | Excel | Python  
**Purpose:** Academic / Business Analytics Research

---

## 🪪 License
This project is licensed under the MIT License — feel free to use, modify, and distribute with proper attribution.
