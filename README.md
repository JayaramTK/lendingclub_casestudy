# Project Name: Lending Club Case Study

## Table of Contents
*	[General Info]
*	[Technologies Used]
*	[Conclusions]
*	[Acknowledgements]

## General Information
### Project Information
-	Understand data to minimize the risk of losing money while lending to customers using EDA techniques in data science. To minimize the credit loss(avoiding defaults).
Project Background
-	This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

### Project Statement
-	To work on the data of the loan applications to find out the strong indicators of default, so as to minimize the credit loss for the banking and financial sector companies.
-	Perform analysis using EDA techniques to understand and pick the driving factors behind loan defaults. The analysis can be utilized by the banks for risk assessment during provision of loans.
Data Set
-	The data set of lending loan is in CSV file format


## Conclusions
### Major Driving factors
-	Annual Income
-	Interest Rate
-	Term
-	Grade

### Considerations for defaults:
•	It’s safer to give loans at 36 months than 60 months
•	Loans of ‘5-10%’ interest are less likely to default, whereas loans of ‘15-20%’ and ‘20-25%’ are more likely to default
•	More safer grades( like grade A,B) are less likely to default, caution to be observed while giving loans of C,D,E,F,G grades
•	Higher income people tend to take high amount loan, so to give high amount loans it’s suggested to target high income people
•	People of higher grades and higher term (60 month) are more likely to default, hence suggest them to take 36month term if they prefer higher grade loans
•	In all loan amount ranges, the lower interest rates are paid back  but higher interest rates are default. To avoid default, it suggested to decrease interest rates
•	Year, home ownership, location have no special impact on the default

### Technologies Used
•	Pandas – 2.0.3
•	NumPy – 1.23.2
•	Matplotlib – 3.6.2
•	Seaborn – 0.12.2

## Acknowledgements
This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.

### Contact
Created by [@JayaramTK] – feel free to contact me!

### License
This project is open source and available without restrictions.





