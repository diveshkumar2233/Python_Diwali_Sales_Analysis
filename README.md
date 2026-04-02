# Python_Diwali_Sales_Analysis
🎆 Python Diwali Sales Analysis

This project is a complete Exploratory Data Analysis (EDA) of Diwali sales data using powerful Python libraries like NumPy, Pandas, Matplotlib, and Seaborn.

It aims to uncover customer purchasing behavior, identify top-performing segments, and generate actionable business insights.

The main objective of this project is to analyze sales data during the Diwali festival and answer key business questions such as:

- ✅ Who are the top customers?
- ✅ Which products/categories generate the most revenue?
- ✅ What age group spends the most?
- ✅ Which states contribute the highest sales?

🛠️ Tech Stack
# 🐍 Python
- 📊 NumPy → Numerical operations
- 🧹 Pandas → Data cleaning & manipulation
- 📈 Matplotlib → Data visualization
- 🎨 Seaborn → Advanced visualizations
📁 Dataset Description

The dataset contains detailed information about customer purchases during the Diwali sales period. Each row represents a transaction made by a customer.

🧾 Columns Explanation:
- User_ID → Unique identifier for each customer
- Cust_name → Name of the customer
- Product_ID → Unique identifier for each product
- Gender → Gender of the customer (Male/Female)
- Age Group → Age category of the customer (e.g., 18–25, 26–35)
- Age → Exact age of the customer
- Marital_Status → Marital status (0 = Unmarried, 1 = Married)
- State → State from where the order was placed
- Zone → Region classification (North, South, East, West, Central)
- Occupation → Customer’s profession (e.g., IT, Healthcare, Govt, etc.)
- Product_Category → Category of the purchased product
- Orders → Number of orders placed
- Amount → Total purchase amount (₹)
- Status → Order status (e.g., Delivered, Cancelled, Returned)
- unnamed1 → Extra/irrelevant column (can be dropped during data cleaning)

# 🔧 Project Workflow
🟢 1. Data Loading
- Imported dataset using Pandas
- Checked basic structure using .head(), .info()

# 🟡 2. Data Cleaning
- Removed unnecessary columns
- Handled missing values
- Changed data types where required

🔵 3. Exploratory Data Analysis (EDA)

# Performed analysis to understand trends:
- Gender-wise spending 💰
- Age group analysis 👨‍👩‍👧‍👦
- State-wise orders 📍
- Occupation insights 💼
- Product category performance 📦

# 📊 Data Visualization
Using Matplotlib and Seaborn, we created meaningful visualizations to understand customer behavior and sales trends.

📈 Key Visuals Created:
# 1.Gender-wise Sales Analysis
-  Compared total purchase amount between male and female customers
# 2.Age Group Distribution
-  Identified which age group contributes the most to sales
 # 3.State-wise Orders
-  Visualized top states with highest number of orders
# 4.Marital Status vs Spending
- Compared spending patterns of married vs unmarried customers
# 5.Occupation Analysis
 - Identified high-spending professions
# 6.Product Category Analysis
-  Highlighted best-selling product categories
# 7.Zone-wise Sales Distribution
- Compared performance across different regions

# 🏁 Conclusion
This project demonstrates how data analysis using Python can uncover valuable insights from real-world sales data.
Through data cleaning, exploration, and visualization, we identified key customer segments, top-performing regions, and high-demand product categories during the Diwali sales period.
