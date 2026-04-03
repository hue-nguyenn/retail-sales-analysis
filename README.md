# INTRODUCTION
This project performs an Exploratory Data Analysis (EDA) on a retail sales dataset to uncover patterns, trends, and relationships that drive sales performance.

Retail sales are influenced by multiple factors such as customer demographics, product categories, and seasonality. Understanding these relationships is essential for generating actionable insights that support business strategy, marketing decisions, and revenue optimization.

# MOTIVATION
The retail sales domain was chosen because it is:
* Highly practical and relevant to real-world business problems
* Widely applicable across industries
* Directly tied to revenue generation and profitability

Sales analysis plays a crucial role in helping organizations understand customer behavior and improve decision-making.

Key Analytical Question: How do customer demographics, product categories, and seasonal trends influence sales?

# TOOLS USED
Python: Entire project is done with Python programming with these libraries:
* Pandas: Used for data manipulation and transformation.
* Numpy: Used in combination with Pandas for preprocessing data.
* Matplotlib + Seaborn: Used for visualizations.


# ANALYSIS 
The EDA focuses on:
* Data cleaning and preprocessing
* Descriptive statistics
* Sales distribution analysis
* Customer demographic insights (age, gender)
* Product category performance
* Time-based trends (seasonality, monthly patterns)
* Correlation and relationship exploration

# KEY INSIGHTS
1. Customer demographics have a strong influence on the spending behaviors.
* With balance distribution of gender, females tend to spend more than their male counterparts, especially in adult and older adult groups.
* Adults are the dominant age group in the dataset, generating the highest revenue. In contrast, young adults are the least presented group, thus contributing the least revenue.
* Despite that, young adults generate the highest average sales per transaction.

2. Product Categories show different patterns between popularity and revenue.
* Clothing is the most sold category by quantity, followed by electronics. However, electronics generates the highest revenue.
* Beauty performs the weakest in both quantity sold and revenue.
* Overall, females prefer beauty while males slight lean towards clothing and electrics.
  
3. Price and Quantity have a strong positive relationship with revenue.
* As price and quantity increase, total sales also increase.
  
4. Seasonal trends strongly influence total sales.
* Sales peaks in May and drops to the lowest in March and September.
* Quarter 2 and quarter 4 perform the best out of 4 quarters, with quarter 4 reaching yearly high.
* Quarter 3 experiences the major drop, driven by the remarkable September decline.
* Average quarterly sales show similar patterns to total quarterly sales.

# KEY TAKEAWAYS
1. Target the high-value customers.
* From the analysis, adults make up a large share of the all age groups and contribute the most to revenue. They should be prioritized in marketing campaigns (such as loyalty programs), especially female adults who tend to spend more.

2. Focus on electronics stocking and pricing management.
* Electronics drive the most revenue, thus focusing on it would help boost more profits.

3. Seasonal trends suggest promotional strategies.
* According to the seasonal trends uncovered, high sales in May and holiday-adjacent months suggests more inventory, staffing and promotions to maximize revenue, while the low sales in quarter 3 suggests potential for campaigns (for example: launch an "End of Summer" clearance or a "Back to Business" campaign) to counteract the revenue dip and build momentum for the October peak.

4. Product category preferences and demand vary across demographics.
* The analysis insights suggest demographic tailored marketing. For example, clothing is a universal category, appealing to both genders and different age groups, or beauty products are favored more by females. Therefore, marketing for new gadgets should target male demographics, while skincare campaigns should prioritize female audiences.
