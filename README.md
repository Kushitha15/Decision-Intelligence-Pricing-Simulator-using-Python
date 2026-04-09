# Decision-Intelligence-Pricing-Simulator-using-Python
1.DISCRIPTION

Developed a pricing strategy simulation model to analyze the impact of price changes on revenue using transactional retail data. 
The project integrates data cleaning, feature engineering, customer segmentation, and elasticity-based demand modeling to simulate 
real-world business scenarios and support data-driven pricing decisions.

2. PURPOSE OF THE PROJECT
The purpose of this project is to evaluate how different pricing strategies influence revenue and customer behavior, enabling businesses 
to make informed decisions that balance profitability and customer retention.

3. DATA SOURCE
Dataset: Online Retail Dataset (UK-based transactions)
Format: Excel (.xlsx)
Features:
InvoiceNo (Transaction ID)
StockCode (Product ID)
Quantity
UnitPrice
CustomerID
InvoiceDate
Country

4. BUSINESS PROBLEM
Businesses often struggle to determine:
How much to increase prices without losing customers
Which customer segments are more sensitive to price changes
What pricing strategy maximizes revenue

👉 This project solves:

“What is the optimal price increase that maximizes revenue while minimizing demand loss?”

5. GOAL OF THE PROJECT
Analyze historical transaction data
Segment customers based on spending behavior
Apply price elasticity modeling
Simulate multiple pricing scenarios (5%, 10%, 15%)
Identify the optimal pricing strategy

6. KEY TECHNIQUES USED
Data Cleaning & Preprocessing
Outlier Handling
Feature Engineering
Customer Segmentation (Low / Medium / High)
Price Elasticity Modeling
Scenario Simulation
Data Visualization
Statistical Testing (SciPy)
Database Integration (SQLAlchemy)

7. VISUALIZATIONS 
🔹 1. Revenue Comparison (Line Chart)
👉 Shows:

Original vs simulated revenue
Trend across scenarios
Insight:

Revenue increases with price across all scenarios

🔹 2. Revenue Growth (%) (Bar Chart)

👉 Shows:

% increase in revenue
Insight:

Higher price increases lead to higher revenue growth

🔹 3. Customer Segment Contribution (Pie Chart)

👉 Shows:
Revenue contribution by segment
Insight:

High-value customers contribute majority of revenue and are less price-sensitive
Link for visualizations:

8. KEY INSIGHTS
Revenue increases with price across all scenarios
A 15% price increase yields the highest revenue
High-value customers are less sensitive to price changes
Low-value customers show higher price sensitivity
Customer segmentation improves simulation accuracy

9. FINAL BUSINESS RECOMMENDATION
Although a 15% price increase maximizes revenue, a 10% price increase is recommended as it provides a balance
between revenue growth and customer retention, reducing the risk of demand loss.
