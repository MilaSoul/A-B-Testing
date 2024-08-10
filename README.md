A/B Testing Analysis for Campaign Performance

Objective:
The primary goal of this A/B testing analysis is to compare the performance of two marketing campaigns:
the Control Campaign and the Test Campaign.
This comparison will help in identifying the better approach to attracting customers, 
marketing products, achieving higher reach, 
and ultimately converting a larger portion of the target audience into actual customers.

Data Cleaning and Preparation:
Missing Values: The control dataset had some missing values, which were imputed with the mean of the respective columns 
Data Renaming: Columns were renamed for consistency and ease of access.
Correlation Analysis: A correlation matrix was created to identify relationships between the variables, 
helping to understand which metrics were strongly related and could potentially influence each other.

Key Analyses Conducted:
Visualization of Spend Distribution:

Histograms and box plots were used to visualize the distribution of spending in both campaigns.
The test campaign had a higher level of investment 
compared to the control campaign, which might influence the performance metrics.

Scatter Plot and Linear Regression:
Scatter plots with linear regression lines were used to analyze the relationship between 
spending and other key metrics like reach, website clicks, searches, etc.
This helped in understanding how spending impacted these metrics differently in both campaigns.

Statistical Testing (t-tests):
Independent two-sample t-tests were performed to determine if the differences in various metrics 
between the two campaigns were statistically significant.
Metrics with p-values less than 0.05 were considered significantly different between the campaigns.

Conclusion:
Test Campaign: Performed better in generating website clicks, which is crucial for online engagement. 
Higher investment in the test campaign also worked well in driving clicks, suggesting that more 
spending might be justified for better results.

Control Campaign: Performed better in "Add to Cart" actions, 
indicating that users in the control group were more likely to show purchase intentions.

