# PROSPER_LOANS
This is a data analysis on Proper Loan company that offers short-term loans (maximum of 60 months) to customers, the data provided will be cleaned, wrangled, visualized and interpreted to ascertain the company's well-being and prospects to the company's stakeholders.
What is the structure of your dataset?
The data set contains 113,937 rows and 0-80 columns but I will be removing some columns outside my scope of analysis and working with the ones I feel are more related to what I want to achieve in this analysis, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. Most of the columns are numeric but also have categorical variables(both numerical and quantitative) also datetime variables.

There are some important features to look at including:

ListingCreationDate: The date the listing was created. LoanStatus: The length of the loan expressed in months. ProsperRating(Alpha): The Prosper Rating assigned at the time the listing was created between AA - HR. Applicable for loans originated after July 2009. Borrower Rate: The Borrower's interest rate for this loan. Borrower State: The two letter abbreviation of the state of the address of the borrower at the time the Listing was created. Borrower APR: The Borrower's Annual Percentage Rate (APR) for the loan. Original Loan Amount: The origination amount of the loan. Monthly Payment: The scheduled monthly loan payment. last Prosper loan. This value will be null if the borrower had no prior loans. Borrower Occupation: The Occupation selected by the Borrower at the time they created the listing.

And many more!


Some columns were removed, some variables replaced to help understand the data better for example the figures for the Listing Category were replaced withe thier variables which helped to decipher the category of loans that defaulted moreand the ones that defaulted less. This information will help The company to know what type of loan to considerate more and less, in making their decisions.

There were some unusual distribution of 'Nan', worng data types, empty spaces etc. for the Nan's I used the mean value of the entire distributions in the column to fill up those spaces for my anaylsis, datatypes were changed to the current data type, changed the column names to lowercases,grouped completed and not completes laons in 0 (not completed) and 1 (completed). All these was done to arrive at what my analysis needs to give to the managment of Prosper Loans.

Some of the relationship observed helped to give a better insight of the company, the relationships helps to show and understand the listing category that gives the highest default and the category that customers pay on time without defaulting. Loan status and number of recommendation shows the higher the recommenadtions the higher we have a completed loan situation, less number recommendation is bad for business. Higher monthly income earners pays ontime too than those with less monthly income(not a good reason too)  

Ofcourse, from the total loans I was able to deduct that Prosper loan needs to work on how to retain their customers because the data shows we have more new ones than old customers. Also, this can be looked at being  loan company people tends to run off more without paying for what they collected which brings to the issue of more stringent conditions.

## Conclusions

Prosper Loan has many insights loaded in the data, is a very loaded date that requires less cleaning (the cleaning was not alot), changing of some datatypes, using the mean value for the 'Nan' most of the null values are relevant to the analysis so I didnt change them. These insights were gotten  from the data used (at the time of listing):
There are more completed loans than not completed ones though we lots of 'bad loans'.
Prosper loans customers as the time of listing were all new customers.
The interest rate paid by employed people is higher than the unmemployed which can lead to alot of 'delinquent loans' as most of them might not be able to meet because of their umemployed start. Prosper loans shouls also keep in mind that some people might fill umeployed to get empathy to get the loan, so alot of verifications needs to be done as it has been proven by this analysis that most of the borrowers claimed income ain't verifiable.
The highest interest rate (annual) of the loans is between 15%-20%.
The highest loan defaulty listing category is the 'RV' which has the lowest interest rate.
Most people with the highest number of recommendations end meeting up with thier obligations than those with less number of recommendation.
Most people with more number of loans pay ontime, meet up their payment than those with less number of loans
The relationship between those with verifiable income and those those with non-verifiable income loan status is not much, though those with verifable income pay their loans more but Prosper loans has more people with non-verifiable income as at the time of listing. 
As a loan business Prosper loan should limit giving out loans to some listing categories that shows inefficiency over time and concentrate on this  categories that brings more returns, ontime payments and those people dont find it too relunctant to pay or even forget as they aint used often.


