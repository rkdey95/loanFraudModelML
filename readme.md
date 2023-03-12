# Problem: Fraud Level Estimation for New Loan Applications

Problem Type: Regression

Written By: Rupesh Kumar Dey

## PROBLEM STATEMENT SUMMARY:
- Financial Institutions are constantly working to assess the risk of loan applicants more accurately. 
- Being good at gauging customer loan risk allows better portfolio management by the company
- This project is pertaining to loan issuance and repayment and their associated fraud level given various features. 
- The aim is to develop a model to predict / estimate loan risk / quality for a given loan application. 

## DATASET: 
- The dataset are comprised of 3 data tables which house information / features regarding
- 1. loan application
- 2. loan repayment
- 3. loan fraud level (by clearfraudscore)

## IMPLEMENTATION:
- This notebook details the Experimentation and implementation of the model development to gauge a loan applications clearfraudscore
- With a given predicted clearfraudscore, the applicant can automatically be flagged by setting a threshold on the fraud score. 
- This will help reduce the burden and process in manually sieving through and processing loan applications and help the company better manage their loan portfolio
- The notebook comprises the end-to-end pipeline for model development consisting of 
- 1) initial data analysis
- 2) feature engineering
- 3) handling missing values
- 4) feature selection
- 5) model development + tuning 
- 6) final proposed solution 

## FYI
- In the process of developing the solution, several process / steps in the feature engineering phase to derive new features took a very long process to generate.
- To derive some features the proecss would take around 1 days to process. 
- In order to ensure reproducability of the entire script and practicality, these processed features were saved externally in the project folder either as JSON files or in CSV files
- These externally saved files would then be reimported and read into the notebook and used for remaining steps. 
- This step is deemed acceptable as the data generated would remain the same across each run as we're using the same raw dataset each time. 
- Due to very large file size and limitations in GITHUB, the data and derived data are stored externally in a shared drive which can be accessed at the following link: https://drive.google.com/drive/folders/1HrS6kj_z7KrBGwA5x2WqeNt4el1vGFGk?usp=share_link

## NAVIGATE THE PROJECT FOLDER

### RAW DATA (AVAILABLE AT https://drive.google.com/drive/folders/1HrS6kj_z7KrBGwA5x2WqeNt4el1vGFGk?usp=share_link)
- located in ./data/data
- Houses the raw data comprised of 
- 1. loan - loan details
- 2. payment - loan repayment details
- 3. clarity_underwriting_variables - loan underwriting details and fraud score details. 

### DERIVED DATA (AVAILABLE AT https://drive.google.com/drive/folders/1HrS6kj_z7KrBGwA5x2WqeNt4el1vGFGk?usp=share_link)
- located in ./derived data
- comprised of JSON and CSV files generated 
- REFER FYI SECTION ABOVE for more details. 

### PYTHON NOTEBOOK
- loanFraudModelNotebook.ipynb
