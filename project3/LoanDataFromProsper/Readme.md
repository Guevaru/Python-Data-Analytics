**(Prosper Credit Loan)
by Olajuwon Abdulbasit Olasubomi
Dataset**

Information about peer-to-peer loans made possible by the credit business Prosper is included in this data set. 113,937 loans with 81 variables are available. I have used the following 13 variables in this investigation: 'Term', 'LoanStatus', 'BorrowerAPR', 'ProsperScore', 'ListingCategory (numeric)', 'EmploymentStatus', 'EmploymentStatusDuration', 'IsBorrowerHomeowner', 'DebtToIncomeRatio', 'StatedMonthlyIncom

Summary of Results
Prosper launched their company in 2005. In 2005, they had just 22 loans. Up until 2008, when it sharply decreased from 11552 loans to 2047 loans in 2009, the number of loans grew. Consequently, starting in 2010, the loan steadily rises, reaching a record-high level in 2013. But, in 2014, it rapidly declines.
The distribution of the borrower's yearly percentage rate looks to be multimodal.Most loan amounts have a right skew with numerous distinct peaks. The most common loan size is $4,000. Three loan terms—12 months, 26 months, and 60 months—are available, with 36 months being the most popular. The majority of the loans are now in progress, and a sizeable portion of them have already been paid off. The past-due debts are divided into six groups based on how many days have passed since their due date. Debt consolidation is the loan category that receives the most requests. The monthly income distribution is right-skewed. With the majority of borrowers reporting monthly incomes of less than $30,000, approximately 5,000 seems to be the most common amount.
Borrower Rate and Loan have a negative relationship with the initial sum. The annual rate percentage for borrowers decreases as loan amounts increase. The term status given for loan payback increases with the loan amount. Loan amounts are larger for borrowers with higher monthly incomes. More monthly income allows borrowers to make larger loan repayments each month. The monthly repayment amount increases as the loan amount does. It is clear that homeowners have a longer employment history than their counterparts, while non-homeowners often received loans between $0 and $5,000 with a maximum of $30,000. Although the majority of homeowners were divided out over various sums between $5,000 and beyond.
The annual rate % for the 36-month term loans ranges from 0 to 0.4, with a few outliers. Loans with a 60-month period are concentrated mainly on larger loan amounts and borrowers with APRs between 0.1 and 0.35, whereas loans with a 12-month term are primarily for smaller loan amounts and borrowers with APRs between 0 and 0.35. Yet, there was no clear correlation between the term and the effects on the borrower's yearly rate percentage.
It was an interesting discovery how the loan terms affected the Monthly Loan Payment that would be made based on the Loan Amount. - Due to the shorter period, monthly fees for loans that last only 12 months are typically higher than those for other terms. But loans with 60-month maturities are more evenly distributed.

Important Takeaways for This Presentation

I concentrated my research for this project on identifying the variables that affect the borrower's annual rate %.

Out of the 81 original variables, I first chose 13 variables, and I then began to examine the distribution of each variable individually using histogram plots for continuous variables and counplots for discrete and nominal variables.

To give a general picture of the variables that have any kind of correlation with one another for the bivariate analysis, I first created a correlation map. I then looked into the relationships between those whose correlations were larger than 0.2.

After that, since the annual rate percentage of the borrower is the most visible aspect, I utilized a regression plot against the loan amount. Then To determine the relationship between two variables, several plots like boxplots, violin plots, and barplots are used.

Thus, based on my findings from the bivariate analysis, it has been concluded that the Loan Initial Amount, Stated Monthly Income, and Monthly Loan Payment are the three factors that have the most influence on the Borrower's annual rate %.

The presentation will demonstrate everything.
