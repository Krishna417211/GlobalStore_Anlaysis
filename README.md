# GlobalStore_Anlaysis
# 📊 Global Superstore Sales Analysis

This project explores and analyzes the Global Superstore dataset to extract valuable business insights that can drive better decision-making. It includes data cleaning, exploratory data analysis (EDA), profit margin calculation, and visualizations to highlight trends and patterns.

## 🔍 Project Objectives

- Understand the sales and profit distribution across various segments and regions.
- Identify the most profitable customer segments and product categories.
- Track sales trends over time.
- Calculate and visualize the **Profit Margin** for better financial insight.

## 📁 Dataset

The dataset includes fields such as:
- Order ID, Order Date, Ship Date
- Country, Region, Segment, City
- Product Category & Sub-Category
- Sales, Quantity, Discount, Profit

## ⚙️ Steps Performed

1. **Data Cleaning**
   - Checked and handled missing values using `dropna()`.
   - Converted date columns (`Order Date`, `Ship Date`) to datetime format.
   - Ensured correct data types for numeric columns like Sales and Profit.

2. **Feature Engineering**
   - Created a new column: `Profit_Margin = (Profit / Sales) * 100`.

3. **Exploratory Data Analysis**
   - Identified top-selling categories.
   - Compared regional sales and profits.
   - Analyzed segment-wise contribution to total sales.
   - Visualized shipping and order time patterns.

4. **Visualizations**
   - Bar plots and histograms for sales and profit trends.
   - Profit margin trends across regions and categories.
   - Time series analysis using Order Date.

## 📈 Key Insights

- **Technology** and **Office Supplies** contributed significantly to profit.
- **Consumer** and **Corporate** segments had the highest number of orders.
- Some regions had high sales but low profit due to high discounts or shipping costs.
- Profit margins varied widely across sub-categories, pointing to optimization opportunities.

## 🛠️ Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Google Colab

## ✅ Conclusion

This analysis helped uncover meaningful trends in global retail sales and highlighted the areas where strategic changes can improve profitability.

## 📎 Repository

All code and visualizations are available here:  
👉 [GitHub Repository](https://github.com/Krishna417211/Netflix_Analysis)
