# Project Name
> Lending Club Case Study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Background: The data shared is from a Consumer Finance company specializing in lending various types of loans. The data consist of 39717 rows spread across 111 columns. One of the columns indicates whether the loan is currently Ongoing, Fully Paid or Charged Off.
- Problem to be solved: Identify patterns based on the columns which would be used to reject/deny loans, reduce the loan amount or charge higher interest rate.
- We have used the Loan Data Set and the associated Data Dictionary to solve the problem.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Borrowers whose dti values lie between 5 – 25 are more likely to default with max defaulters lie between 15-20.
- Borrowers who live in Rented homes or paying mortgages are more likely to     default. 
- Consumers who borrow due to Debt consolidation are more likely to default.
- Grades 'B','C','D' and 'E' have higher defaults as compared to 'A','F' and 'G'. Within these grades, there are no huge variations observed with these plots.	
- Loan amount for charged off loans span between 900 - 35K. Analysis of loan data indicates many are smaller loan size, with more defaults happening between USD 0-7000 followed by 7K-14K and 14K-21K.
- More the number of accounts, more the default – this is only true for consumers having upto 30 accounts. In any case, more than 30 accounts does not indicate possibility of default. The plot of open Accounts follow similar to normal curve with the peak of the charge off lying between 6 - 8 accounts having maximum default.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas
- matplotlib
- seaboarn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements


## Contact
Created by [@anonnihcas] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->