# LendingClub_Risk_Analysis

LendingClub is a financial service company specializing in personal loans, business loans, auto loan refinancing, and banking solutions. Founded in 2007, LendingClub has helped over 5 million customers consolidate debt, pay off credit cards, and borrow money for "almost any purpose". 

In this case study, we will be able to analyze accepted and rejected loans ranging from 2007 to 2018, and build two classification models to determine if a loan will be rejected or accepted based on the borrower, and the risk involved with accepting a loan. We will be able to develop a basic understanding of creditworthiness, credit analysis, and financial risk by probabilistically modeling how borrower features relate to defaulted or charged-off loans.

By building a Naïve Bayes Classification model, we can assume conditional independence among a pool of features, allowing us to calculate joint probabilities and calculate the numerical percentage of risk involved with a given loan. This will enable us to predict if an approved loan will be defaulted or charged-off. 

Additionally, we can predict if a loan request will be approved or declined by utilizing a Nearest Neighbor model. In other words, we can predict the creditworthiness and risk associated with a loan application based on our data, and classify whether it will be accepted or rejected. 


Source: LendingClub. “Personal Loan.” LendingClub. https://www.lendingclub.com/personal-loan


# STEP BY STEP GUIDE: 

Before diving in, please download the required .csv files: 
- "lendingclub_column_definitions.csv"
- "accepted_2007_to_2018Q4.csv" (Found in the Google Drive Folder)
- "rejected_2007_to_2018Q4.csv" (Found in the Google Drive Folder)

After downloading the necessary .csv files, download and open "Blevins, Alec - LendingClub Risk Analysis.ipynb"

Follow along and enjoy! 

# Contents: 

- Cover & Importing Our Data
- Part 1: Naïve Bayes Classification for Defaulting and Charged Off Loans
    - Exploratory Data Analysis & Data Scrubbing - Accepted Loans
    - Correlation Analysis
    - Naïve Bayes Classification Implementation
    - Lazy Evaluation
    - K-Fold Cross Validation
    - Part 1: Summary
- Part 2: Nearest Neighbor Algorithm for Accepted & Rejected Loans
    - Exploratory Data Analysis & Data Scrubbing - Rejected Loans
    - Nearest Neighbor Algorithm Implementation
    - K-Fold Cross Validation
    - Part 2: Summary
- Conclusion

