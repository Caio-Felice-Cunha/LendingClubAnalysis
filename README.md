# Lending Club Analysis
Clean and pre-process the data with Python Numpy<br>
[Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTkwMDg3ZjQtMzFmZC00MmI4LWIzMDctZDFhOGQzODZiOTlkIiwidCI6IjA4OTM0YTNmLWFkNmUtNDgzZS1hNjhlLTUxYWI3OTI1YmFiNyJ9) <br> 
[Power BI Power App](https://app.powerbi.com/Redirect?action=OpenApp&appId=f6eebfe2-d3d9-472c-82d9-ddd925f736b9&ctid=08934a3f-ad6e-483e-a68e-51ab7925bab7)

<img align="center" src=https://user-images.githubusercontent.com/111542025/226971228-d74318e7-66ad-4aee-b79b-41813e514684.png>

## This is the 2nd version
### Improvements compared to the last version:
* Power BI Dashboard (Report)

## Business Problem
> Data source: https://www.openintro.org/data/index.php?data=loans_full_schema. Data source for quotation: https://finance.yahoo.com/

LendingClub is a financial services company. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission, and to offer loan trading on a secondary market.<br>
The first problem that will be solved is the one involving the dataset that needs several adjustments.<br>
So the main problem to be solved at this moment is to clean and pre-process the data.<br>
Note: We used the dataset available at the link above as a source of data, but we made changes to the data to make it even more problematic.

## Business Assumptions
We assume that the company wants an analysis of the dataset provided, but for this analysis to take place, the data must first be processed.

## Solution Strategy
For data cleaning and pre-processing, we use several data science techniques to handle null and categorical values.<br>
We chose the Python language and the Numpy library, due to their efficiency and speed.
* Step 01: Import the data and analyze the quality of it;
* Step 02: Checking for Missing Values;
* Step 03: Manipulating String Columns;
* Step 04: Preprocessing the issue_date Variable with Label Encoding;
* Step 05: Pre-Processing of the variable loan_status with Binarization;
* Step 06: Pre-Processing the term Variable with String Cleanup;
* Step 07: Pre-Processing Grade and sub_grade Variables with Dictionary (Like Label Encoding);
* Step 08: Pre-Processing the Verification Status Variable with Binarization;
* Step 09: Pre-Processing the url Variable with ID Extraction;
* Step 10: Pre-Processing of the Address Variable with Categorization;
* Step 10: Converting the array;
* Step 11: Manipulating Numeric Columns;
* Step 12: Pre-Processing the funded_amnt, Loan_amnt, int_rate, installment and total_pymnt Variable;
* Step 13: Building the Final Dataset;
* Step 14: Writing the Final Clean and Pre-Processed Dataset.



## Next Steps
* Accepting suggestions

## Disclaimer
A good part of this project was largely done in the Data Science Academy, Big Data Real-Time Analytics with Python and Spark course (part of the Data Scientist training)
