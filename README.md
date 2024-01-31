**Problem Statement**
The problem addressed by the Loans dataset is the challenge of identifying the key factors that can predict whether or not an individual is likely to default on a loan. This is an important issue for financial institutions, as lending to individuals who are likely to default can result in significant financial losses. The Loans dataset aims to provide insights into this problem by identifying the variables that are most strongly associated with loan defaults. By analysing these variables, financial institutions can identify and avoid risky loan applicants, which can help to reduce their overall risk exposure and ensure that their lending practices are both responsible and sustainable. The problem of loan default is a significant challenge for financial institutions, and the Loans dataset provides an important tool for addressing this issue and improving lending practices.


**Data Description**
The data contains the complete loan data for all loans issued through the time period 2007 to 2011.


**Data Dictionsary**
No.	Column Name	Description
1	annual_inc	The self-reported annual income provided by the borrower during registration
2	dti	A ratio calculated using the borrower’s total monthly debt payments on the total debt obligations, excluding mortgage and the requested LC loan, divided by the borrower’s self-reported monthly income.
3	emp_length	Employment length in years. Possible values are between 0 and 10 where 0 means less than one year and 10 means ten or more years.
4	grade	LC assigned loan grade
5	funded_amnt	The total amount committed to that loan at that point in time.
6	funded_amnt_inv	The total amount committed by investors for that loan at that point in time.
7	id	A unique LC assigned ID for the loan listing.
8	installment	The monthly payment owed by the borrower if the loan originates.
9	last_pymnt_amnt	Last total payment amount received
10	int_rate	Interest Rate on the loan
11	last_pymnt_d	Last month payment was received
12	loan_amnt	The listed amount of the loan applied for by the borrower. If at some point in time, the credit department reduces the loan amount, then it will be reflected in this value.
13	loan_status	Current status of the loan
14	member_id	A unique LC assigned Id for the borrower member.
15	purpose	A category provided by the borrower for the loan request.
16	term	The number of payments on the loan. Values are in months and can be either 36 or 60.
17	total_acc	The total number of credit lines currently in the borrower's credit file
18	total_pymnt	Payments received to date for total amount funded
19	total_pymnt_inv	Payments received to date for portion of total amount funded by investors
20	total_rec_int	Interest received to date
