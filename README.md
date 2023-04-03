# Bank_Personal_Loan_Modelling

This repository contains a Jupyter Notebook Bank Personal Loan Modelling.ipynb which demonstrates data exploration and the creation of various machine learning models using a sample dataset (Bank_Personal_Loan_Modelling.csv) that contains information about bank customers who either accepted or rejected the personal loan offer.

# Dataset
## The dataset contains the following features:

 ID: Customer ID
 
 Age: Age of the customer
 
 Experience: Years of experience of the customer
 
 Income: Annual income of the customer
 
 ZIP Code: ZIP code of the customer's location
 
 Family: Number of members in the customer's family
 
 CCAvg: Average spending on credit cards per month
 
 Education: Education level of the customer
 
 Mortgage: Value of the house the customer lives in
 
 Personal Loan: Whether the customer wants a personal loan or not (1=Yes, 0=No)
 
 Securities Account: Whether the customer has a securities account with the bank or not (1=Yes, 0=No)
 
 CD Account: Whether the customer has a certificate of deposit account or not (1=Yes, 0=No)
 
 Online: Whether the customer uses online banking services or not (1=Yes, 0=No)
 
 CreditCard: Whether the customer has a credit card or not (1=Yes, 0=No)

# Installation
The following Python libraries are required to run this code:

pandas

 numpy
 
 matplotlib
 
 seaborn
 
 math
 
 pandas_profiling
 
 scipy
 
 plotly
 
 bubbly
 
 sklearn
 
 mlxtend

# Usage
After cloning the repository, open the Jupyter Notebook Bank Personal Loan Modelling.ipynb in Jupyter and run the cells to execute the code. The notebook contains markdown cells with descriptions of the steps and the code cells are commented to explain what each line does.

# Results
In the notebook, the data is first explored using descriptive statistics, data visualization, and data cleaning techniques. This includes the creation of a function check() to check the dataframe for columns, data types, unique values, and null values, as well as the removal of the 'ID' column and cleaning the 'Experience' and 'ZIP Code' columns.

Several machine learning models are then created using scikit-learn, including K-Nearest Neighbors, Logistic Regression, Gaussian Naive Bayes, Decision Tree, Random Forest, and Support Vector Machine. Cross-validation is used to evaluate the models and the results are displayed in a table.

Finally, a visual representation of the relationship between age, experience, income, mortgage, and acceptance of personal loan offers is created using the bubbleplot() function from the bubbly library.


