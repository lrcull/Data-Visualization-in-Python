# Data-Visualization-in-Python

Can We Predict Who Will Default On A Loan?
by Leslie Culliton


Dataset – Loan Data from Prosper (prosperLoanData.csv)

The data set contains information about 113,937 loans and 81 variables that are tracked with the loans. A new data set was created using 10 variables from the original data set.

Summary of Findings

The following variables from the prosperLoanData.csv file were analyzed:

LoanStatus
BorrowerRate
EmploymentStatus
CreditScoreRangeUpper
CreditScoreRangeLower
OpenRevolvingAccounts
OpenRevolvingMonthlyPayment
IncomeRange
LoanOriginalAmount
MonthlyLoanPayment
DelinquenciesLast7Years

Each of the variables was plotted to determine how it behaved over the data set. There were no surprises in the data when looking at the individual variables. Borrower rates were clustered between 0.1 and 0.3. Most loans were provided to individuals who were employed, had high credit scores and income ranges, low numbers of open revolving accounts and delinquencies, and low monthly payment obligations prior to loan origination.

The bivariate plots show that income range, employment status, and credit score affect loan amount. The number of revolving accounts, monthly payments, and past delinquencies are indicators that loans may default.

The number of open revolving accounts affects monthly loan payment. This makes sense, as number of revolving accounts is an indicator of loan default.

Interestingly, the data did not behave as expected when past delinquencies were plotted with monthly payment amounts prior to loan origination. These variables have a slightly negative correlation. When plotted with loan status, individuals with few past delinquencies and low loan amounts were more likely to be past due or to default than were individuals with either high incidents of delinquencies or high monthly payments. Also, there are lower rates of past due payments or default when the loan amount is high and the borrower rate is low.

Key Insights for Presentation

•	The number of revolving accounts, monthly payments, and past delinquencies are indicators that loans may default.
•	Although high numbers of past delinquencies and high monthly payments are indicators that a loan may default, borrowers who have either past delinquencies or high monthly payments are less likely to default.
