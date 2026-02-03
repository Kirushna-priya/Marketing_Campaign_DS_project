MARKETING CAMPAIGN

Problem scenario: 
Marketing mix stands as a widely utilized concept in the execution of marketing strategies. It encompasses various facets within a comprehensive marketing plan, with a central focus on the four Ps of marketing: product, price, place, and promotion.

Data description:
The dataset aligns with the Four Ps of Marketing, categorizing variables to analyze consumer behavior. Product-related variables track spending across categories, while Price factors like income and deal-based purchases indicate affordability. Place covers shopping channels and web visits, reflecting purchase preferences. Promotion measures campaign engagement, complaints, and recency. Additionally, demographics support segmentation for personalized marketing. This structured approach helps businesses optimize products, pricing, distribution, and promotions for better customer engagement and market performance.

Objective: 
To conduct exploratory data analysis and hypothesis testing to enhance comprehension of the diverse factors influencing customer acquisition for a particular company.

Problem Statement: 
1.	Categorizing variables to analyse consumer behaviour.
2.	Analysing product-related variables to track spending across categories
3.	Analysing purchase preferences among three different channels and their effects on each other.
4.	Access the efficacy of campaigns
5.	Access the customer background who raise complains.
6.	Analysing demographic support for personalized marketing.

This structured approach helps businesses optimize products, pricing, distribution, and promotions for better customer engagement and market performance.

Approach: 
The analysis was performed on Jupyter Notebook using Python programming language.
The libraries which were used include Numpy, Pandas, Matplotlib, Seaborn, Scipy and Scikitlearn.
Concepts employed include:
1.Checking missing values using isna()
2.Filling the Nan values using fillna()
3.Cleaning the data entries of particular column using if conditions.
4.Checking for duplicates using duplicated().sum().
5. Creating new columns by adding different columns for easy analysis.
6.Checking for outliers by a. using boxplot (to visualize which column has outliers), b. using IQR and function (to find outlier entries of that particular column), c. using clipping (to treat outliers).
7.Using correlation Values for finding patterns between different columns.
8.Using Hypothesis testing, independent or two sample t test and paired t test for concluding hypothesis statements.
9.Using graphs for visualizing trends among different categories.

Insights:

1.Strongest Positive Correlations

•	Wines & Total Spend: 0.89
Spending on wines has a very strong positive relationship with overall expenditure.

•	Number of store purchases & Total Purchase: 0.86
Store purchases strongly drive overall purchase count.

•	Meat Products & Total Spend: 0.84
Meat product purchases strongly contribute to the total spent.

•	Income & Total Spend: 0.80
Higher income is strongly related to more spending.

2.Strongest Negative Correlations

•	Meat Products & Children: –0.50
Families with more children tend to purchase less meat products.

•	Kids at home & Number of catalogue Purchases: –0.50
More kids at home, fewer catalogue purchases.

•	Income & Kids at home: –0.52
Higher income is associated with fewer kids at home (possibly due to demographic factors).

•	Income & Number of website visits per month: –0.65
Higher income customers tend to visit the website less often.

3.Additional patterns:

•	Product spendings (wines, meat, fruits, etc.) are all highly correlated both with each other and with overall spending.

•	Website visits have strong negative correlation with income and product purchases, implying website browsing may not lead to high-value purchases.

4.Hypothesis Testing proved following:

•	Older individuals lean towards traditional instore shopping.

•	Customers with children have a higher average online shopping activity.

•	Sales through alternative channels cannibalize store purchases.

•	U.S. customers' average total purchase volume is equal to (or less than) that of international customers.

5.Visualizations showed following:

•	Top-performing product: MntWines and the Lowest revenue product: MntFruits
•	Age and the tendency to accept the last campaign show negative linear 
Correlation.
•	The country with the highest number of customers who accepted the last camp-aign was Spain.
•	The number of children present and the total expenditure show negative linear -relationship.
•	Graduated people have raised more complains than post-graduated ones.


Conclusion: 
1.	Increase marketing for high value products like wine and meat.
2.	Number of online purchases are less, so promote more online purchases and make give discounts over online than on store to attract more buyers.
3.	People with kids are already using online purchases so try to show them high value products more so that they buy more value through online purchases.
4.	Make online purchase interface user friendly to ease purchases for older individuals.



