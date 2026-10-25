 BrightMart Retail Intelligence and Sales Forecasting

 Project Overview

BrightMart Retail Intelligence and Sales Forecasting is a Python-based data analytics and machine learning project designed to analyze retail sales performance and forecast next-month product demand.

The project explores sales revenue, profitability, advertising expenditure, customer ratings, discounts, inventory availability, and product demand to generate useful business insights.

 Business Objectives

- Analyze sales performance across products and regions.
- Calculate revenue, total cost, and profit.
- Identify relationships between advertising expenditure and revenue.
- Examine customer ratings, discounts, and inventory levels.
- Forecast next-month units demand using machine learning.
- Provide evidence-based recommendations for management.

 Tools and Technologies

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Random Forest Regression
- GitHub

 Dataset Description

The dataset contains retail transaction and business information, including:

| Column | Description |
|---|---|
| Transaction_ID | Unique transaction identifier |
| Date | Transaction date |
| Region | Sales region |
| Product | Product category |
| Units_Sold | Number of units sold |
| Unit_Price | Price per unit |
| Cost_Per_Unit | Cost per unit |
| Advertising_Spend | Advertising expenditure |
| Customer_Rating | Customer satisfaction rating |
| Stock_Available | Available inventory |
| Next_Month_Units_Demand | Target variable for demand prediction |
| Revenue | Sales revenue |

The products analyzed include laptops and monitors.

 Data Analysis and Visualizations

The project includes visualizations covering:

- Advertising Spend vs Revenue
- Total Profit by Product
- Average Customer Rating by Product
- Average Stock Available by Product
- Sales Revenue Trend Over Time
- Advertising Spend vs Customer Rating
- Discount Percentage vs Units Sold
- Actual vs Predicted Next-Month Demand
- Feature Importance for Next-Month Demand

 Machine Learning Model

A Random Forest Regressor is used to predict next-month units demand.

 Model Features

- Units_Sold
- Unit_Price
- Cost_Per_Unit
- Advertising_Spend
- Customer_Rating
- Discount_Percent
- Stock_Available

 Evaluation Results

The current notebook reports the following results:

| Metric | Result |
|---|---:|
| Mean Absolute Error (MAE) | 1.89 |
| Root Mean Squared Error (RMSE) | 2.19 |
| R² Score | 0.929 |

These results indicate that the model fits the evaluated data well. Further validation is needed to confirm performance on genuinely future observations.

 Key Findings

1. *Product profitability:* Laptops generated a higher total profit than monitors in the analyzed dataset.
2. *Advertising and revenue:* The scatter plot shows a positive relationship between advertising expenditure and revenue for both products.
3. *Customer ratings:* Laptops received a higher average customer rating than monitors.
4. *Inventory availability:* Monitors had higher average stock availability than laptops.
5. *Demand prediction:* Units sold was the most important feature in the current Random Forest model.

These findings describe the analyzed dataset and should not automatically be interpreted as causal relationships.

 Management Recommendations

1. *Optimize product inventory:* Use demand forecasts and stock availability to improve replenishment planning and reduce stockout or overstock risks.
2. *Review advertising effectiveness:* Compare advertising expenditure with revenue and profit to identify opportunities to improve marketing efficiency.
3. *Improve monitor customer satisfaction:* Investigate customer feedback and product issues to identify opportunities to improve monitor ratings.
4. *Plan product-specific promotions:* Evaluate discount levels alongside units sold and profit before expanding promotional campaigns.
5. *Monitor forecast accuracy:* Regularly compare predicted demand with actual demand and retrain the model when performance declines.

 How to Run the Project

1. Install Python and Jupyter Notebook.
2. Install the required libraries:

   bash
   pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
   

3. Download or clone this repository.
4. Place the dataset in the location expected by the notebook.
5. Open BrightMart_Sales_Analysis.ipynb in Jupyter Notebook.
6. Run the notebook cells in order.

 Project Files

- BrightMart_Sales_Analysis.ipynb — Data analysis, visualizations, and machine learning.
- README.md — Project documentation.
- Dataset — Include the dataset if you have permission to share it, or provide an appropriate dataset reference.

 Limitations

- Model performance depends on dataset quality and representativeness.
- A random train-test split may not reflect real-world future forecasting performance.
- Feature importance indicates predictive contribution, not causation.
- Results should be validated using chronological holdout data before business deployment.

 Conclusion

This project demonstrates how Python-based analytics and machine learning can support retail decision-making through sales analysis, profitability assessment, inventory planning, and demand forecasting.

 Author

Ananthur

GitHub: [ananthur148-jpg](https://github.com/ananthur148-jpg)


 Management Recommendations

1. *Improve demand forecasting:* Units Sold has the highest feature-importance score (approximately 85.2%). Use demand forecasts to plan inventory.

2. *Optimize advertising:* Advertising Spend has a feature-importance score (approximately 7.6%). Compare marketing costs with revenue before adjusting budgets.

3. *Improve inventory planning:* Monitors have higher average stock availability than laptops in the analysis. Review demand forecasts and stock levels to balance inventory.
