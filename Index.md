## Intelligent Loan Application Approver

* A non-banking financial institution (NBFI) or non-bank financial company (NBFC) is a Financial Institution that does not have a full banking license or is not supervised by a national or international banking regulatory agency. NBFC facilitates bank-related financial services, such as investment, risk pooling, contractual savings, and market brokering.

* An NBFI is struggling to mark profits due to an increase in defaults in the vehicle loan category. The company aims to determine the client’s loan repayment abilities and understand the relative importance of each parameter contributing to a borrower’s ability to repay the loan. 

### Goal

* The goal of the problem is to predict whether a client will default on the vehicle loan payment or not. For each ID in the Test_Dataset, you must predict the “Default” level.

### Datasets

* The problem contains two datasets, Train_Dataset and Test_Dataset. Model building is to be done on Train_Dataset and the Model testing is to be done on Test_Dataset. The output from the Test_Dataset is to be submitted to the Hackathon platform.

### Metric to measure

* The metric to measure is the F1_Score. F1_Score is the harmonic mean of Recall and Precision. In this Hackathon, you will get the F1_Score of 1. Please visit the link for more details on [F1 Score](https://en.wikipedia.org/wiki/F-scoreThe)

### Submission File Format:

A CSV file with exactly 80900 entries plus a header row.

File should have exactly two columns

* ID (sorted in any order)
* Default (contains 0 & 1, 1 represents default)
