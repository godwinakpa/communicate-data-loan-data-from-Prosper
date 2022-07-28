## Prosper-Loan-Data-Analysis

### by _Godwin Akpa_


## Dataset

The Prosper loan dataset comprises of 113937 loan entries with 81 attributes on each loan, from the year 2009-2014. There are two main categories of the attributes:

1. Borrower information: Basic attributes of the borrowers such as annual income, condition of employment, interest rate, loan status, etc.
2. Historical loan performance Metrics: Metrics evaluating the risk associated with the loans such as Prosper score, Prosper rating and Borrower APR, etc. 
Nevertheless, there were some elements that I needed to fix, in order to create interesting and trustworthy analyses and visualizations.


## Summary of Findings

The objective of this work is to investigate factors affecting borrower rate and loan amount:
In the exploration, I found out that there was a moderate and negative correlation between interest rate and Loan amount. Also, there is some negative and strong relationships between the categorical/ordinal variables selected and the interest rate. As pointed out below:

**Findings**
1. Most borrowers have a good standing with Prosper majority of which have earned C Rating while ratings B, A & D makes up for the other three highest Rating. Meanwhile the lowest Credit Rating is the AA Prosper Rating(with less than 10%).
2. The majority of borrowers are employed, which is evident because it wouldn't be easy to get a loan without a job.
3. Majority of the loans was taken to be utilized for Auto, Business, Home Improvement as well as for Debt Consolidation.
4. The three most common loan sizes that people took out are 4K, 10K, and 15K. Consequently, the majority of borrowers who have taken out credits are the medium income earners and have an average monthly salary between 3,000 dollars and 20,000 dollars.
5. The investors plot shows that most of the loans were singly-funded (had single investors). The investors however have a bias and preference for investing with borrowers with higher prosper score and rating.
6. Except for AA (with income range 100,000 dollarsand above), all the borrowers regardless of their prosper rating has an income range between 25,000 dollars and 74,999 dollars which further buttresses the fact that medium income earners requested for most loans from Prosper.
7. Its worthy of note that, more restrictive credit condition (higher rate) is applied to Medium and Long term loans than the short term loans.
8. As expected, rates for individuals with collateral(homeowner) are lower than those without collateral but the gap between the rate has decreased significantly since 2011. Also and investors tend to invest more with borrowers with collateral. Meanwhile, there has been a continuous decline in the number of investors in the loan requests of borrowers (regardless of their collateral) except for a slight stability between 2011 and 2012.

**Conclusion**
There is a moderate and negative correlation between interest rate and loan amount. This corresponds to negative/strong relationships between the categorical/ordinal variables selected and the interest rate. For example, Unemployed borrowers, borrowers without collataral, borrowers with poor loan status (Defaulted, ChargedOff and Past Due) and those with low Prosper Score, Prosper Rating, stated monthly income and income ranges (less than 25,000 dollars) have more restrictive credit condition (higher rate) than the those who have jobs, collataral, good loan status (current, Final payment in Progress or completed) and high Prosper Score, Prosper Rating, stated monthly income and income ranges (25,000 dollars and above).
Thus, I can conclude that these variables are the most excellent determinant factors of borrower's interest rates and loan amount. 


## Key Insights for Presentation

For the presentation, I focus on just the influence of some variables on interest rate and loan amount. I started by introducing key insights gotten from the analysis then plot their distribution.

Afterwards, I have used violin plots, box plots and line plots to dig deeper on the relationship between my variables of interest (interest rate and loan) and the explicative variables.
I use the violin plots of interest rates and loan amount across ProsperScore, Employment Status, Collateral, and Prosper Rating. I'm only looking at the relationship plots here since it's the clearest example of how the categorical variables affect interest rates and loan amount. The other categorical variables, Term, Income Range, Income Group and Loan Status are also covered, using boxplot, point plots and line plots. I've made sure to use the proper color palettes across the presentation to make sure it is clear and drives the points I am making.