# churn-prediction-data-analytics



In a bank an outflow of customers has been noticed for some time - that's about 16% over the past year. However, at this point no one has been able to identify the factors that may have caused this. As analysts, we have been engaged in this task in order to find the cause of the problem, based on which the next steps will be defined. Moreover, an additional result of the analysis is expected to be the selection of a group of customers against whom the bank should focus its efforts at this point to prevent their departure.

On the basis of the expertise of those who serve retail customers, the IT team has prepared a set of data that will serve us in further analysis.

Data set imported from Kaggle

Pandas library used to analyze the data


**Summary**


Since things are getting worse at the company, we were asked to analyze one of its areas - credit cards. We received information that an increase in the number of customers who stopped using their credit card was observed this year.

In order to conduct the analysis, we used a dataset from the Kaggle platform - Credit Card customers, with the help of which we simulated a real task.

The first step of our task consisted of exploratory data analysis. During it, we analyzed categorical variables, which we used to extract information flowing from the resource. Importantly, in the process we extracted two variables - Total_Trans_Amt_agg and Total_Trans_Ct_agg, which allowed us to divide our population into two smaller ones, which differed primarily in the percentage of deactivated credit cards.

By dividing the population into two groups, we were able to compare them with each other and identify significant differences, through which we found that cards held by:

men (+6%),
married individuals (+7.6%),
customers who have held the card for up to two years (+6.7%),
people up to 40 years old (about +6%, depending on the category)


In this way, we identified a potential group to whom, for example, additional credit card promotions could be targeted, which would induce these people to continue using the card. Another example could be some sort of discount for using the card for more than two years (such as a lower interest rate, raising the limit, extending repayment terms), perhaps after this period the customer becomes attached to the card.
