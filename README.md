The dataset belongs to firm Dunnhumby, a retail and customer data science firm and made available through Kaggle. Tables are merged to create the sub dataset of 801 households with 47 factors
under all the categories.

Marketers frequently employ coupons as a significant promotional strategy across various consumer product sectors. 77% of the United States population uses coupons and shoppers saved more than $3 billion last year by doing so. Coupon users report an average of 11.5% savings on
their grocery bill with coupons, prompting manufacturers to respond by offering more than $250 billion in coupon savings in 2003 (Somjit Barat, Lilly Ye, 2015). From a managerial perspective, it is very important to figure out factors that affect 
coupon redemption, so that marketers can design effective coupons in accordance with their promotional objectives. Many researchers have been trying to identify critical factors in coupon redemption (Boon Young Lee, 2004). Through empirical analysis and visual representation of data, this paper aims to show if marketing campaigns affect household purchases. The hypothesis are as follows:
H0: Exposure to marketing campaigns does not significantly affect the amount spent by retail households considering demographic factors such as income, household size, marital status. HA: Exposure to marketing campaigns significantly affects the amount spent by retail households considering demographic factors such as income, household size, marital status.

Exploratory Data Analysis
![image](https://github.com/tatevikhak/Marketing-and-Household-Spending/assets/166149374/e1e4557d-8883-4bcb-a71f-cddf57d3e2aa)
Summary statistics for numerical independent variables
![image](https://github.com/tatevikhak/Marketing-and-Household-Spending/assets/166149374/62f72d97-d01b-427f-83cb-e16381a402e4)

Distribution of households across different income categories
![image](https://github.com/tatevikhak/Marketing-and-Household-Spending/assets/166149374/8b58688f-d4c0-4a63-8fec-b7f271619705) ![image](https://github.com/tatevikhak/Marketing-and-Household-Spending/assets/166149374/2575a99b-efcc-41a9-8272-b13bf1fb3049)

Marketing and Household Spending 

The ANOVA results revealed statistically significant differences in both total campaign receipts across different income categories.

![image](https://github.com/tatevikhak/Marketing-and-Household-Spending/assets/166149374/9ce7e932-228f-4eac-9520-74de88487cee)

One-way ANOVA for total campaign received and total coupon redemption across income categories

![image](https://github.com/tatevikhak/Marketing-and-Household-Spending/assets/166149374/c72d55cc-14b4-430c-9e6d-64ead823d919)

Campaign received and Coupon redemption variance across income categories

The results of the regression model are attached in the table below. The p value of multiple factors shows their significance level when compared with 0.05 alpha. Analysis shows that most factors do not have a significant effect on the total_sales, however factors such as
total_typeB_coupon_redm, total_distinct_product_manufacturer, total_distinct_department, yeojoohnson_total_coupon_disc, total_dist_campaign_redm, had significant impact with p-values less than 0.05.
Based on results, see that campaign_received variable is not significant for amount spent and thus, just having a marketing intervention does not impact the amount spent. However, the total different campaigns that were redeemed, having distinct products in their basket, and having products from different departments were effective in impacting the amount spent.
![image](https://github.com/tatevikhak/Marketing-and-Household-Spending/assets/166149374/a0080be4-1f4d-4631-8f4e-e07ddab12400)
Multivariate regression results
The results of the analysis help businesses decide the marketing strategies and answer questions such as what number of campaigns should be launched? Should a single campaign/coupon cover multiple products or different campaigns for different products? Regression provides insights on impact of various factors and this can help businesses decide by taking into account an
individual’s firm's context. The aim should be to increase the redemption of unique campaigns so sending out a high frequency of campaigns to begin with should be considered. Additional analysis such as ANOVA also shows that there are certain areas where campaign metrics vary
depending on the income categories, thus indicating a more tailored approach for different customer segments.






