Food-Delivery-Cost-and-Profitability-Analysis
Project Overview
This project aims to analyze and optimize the costs and profitability of a food delivery service. The dataset consists of detailed records of 1,000 food orders, including order values, delivery fees, discounts, commission fees, and other related costs. The primary goal is to understand the cost structure, identify profit margins, and provide recommendations for improving profitability.

Key Features and Techniques
Data Loading and Preparation:

Loaded the dataset using pandas and converted date-time columns to appropriate formats.
Extracted and processed discount information from the 'Discounts and Offers' column.
Feature Engineering:

Calculated the 'Discount Percentage' and 'Discount Amount' for each order.
Computed total costs for each order by summing delivery fees, payment processing fees, and discount amounts.
Calculated revenue and profit for each order.
Exploratory Data Analysis (EDA):

Analyzed the distribution of profits per order using histograms.
Visualized the breakdown of total costs using a pie chart.
Compared total revenue, costs, and profit using a bar chart.
Profitability Simulation:

Filtered for profitable orders and calculated average commission and discount percentages.
Simulated profitability using recommended commission (30%) and discount (6%) rates.
Visualized the comparison of actual vs. simulated profitability.

Results and Insights
Overall Metrics:

Total Orders: 1,000
Total Revenue: 126,990 INR
Total Costs: 68,502 INR
Total Profit: 58,488 INR
Profit Distribution:

Visualized the profit distribution per order using a histogram.
Identified the mean profit per order.
Cost Breakdown:

Delivery Fee: 40.8%
Payment Processing Fee: 37.4%
Discount Amount: 21.8%
Profitability Simulation:

Recommended commission percentage: 30%
Recommended discount percentage: 6%
Simulated profitability showed a potential increase in profit density with recommended rates.
Conclusion
This project provides a comprehensive analysis of the costs and profitability of a food delivery service. By examining detailed metrics and visualizations, it offers actionable insights into optimizing discounts and commissions to enhance overall profitability. The simulation of recommended rates demonstrates the potential for improved financial performance, making this analysis valuable for strategic decision-making in the food delivery industry.
