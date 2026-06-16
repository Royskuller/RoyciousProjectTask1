# RoyciousProject
1) Get the dataset from Kaggle raw dataset of supermarket_sales.csv
2) Cleaned dataset will be Supermarket_sales_Transform.csv
3) CLEANING OF DATE COLUMN: The date column was not clean e.g. 1/21/2019 (Month/Day/Year) which is not standardized for us to see. The Cleaned column will be Date_Constructed. Steps that I do 1) Duplicate the unclean date, 2) Split Day, Month, Year by delimeter, 3) Create Custom Column Date_Constructed column using formula = #date([Year],[Month],[Day]) and finally change the datatype to Date
4) Round up the Unit price, Tax 5%, Total, cogs, gross margin percentage, gross income columns to 2 decimal place as standardization
5) No duplication or null or empty values was found in the dataset.
6) Time was converted from e.g. 18:00 to 6:00:00pm as standardization
