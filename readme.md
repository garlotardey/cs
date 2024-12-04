link for slides
https://docs.google.com/presentation/d/1tRoB3EIFWCCr4_L_5GiZfNxh5NvSZtBjO23ndr3UeyI/edit?usp=sharing

for the cleaned data
removed outlires for selling price using 1st quartile and 3rd quartile the iqr is the diffrences of the 2 this removed outlires that might distort the data.
then i used one hot encoding on fuel type, seller type tranmission and owner converting them into 1 or zeros
for the year colmn i used feture enginering for to convert it into numeric values wich removed some null values and created a new column called age.
Handelled missing values in the Kms_driven column and filled them with the median of the colmn.
I standerdized the data woth numerical cols on selling price, kms, driven, and age giving them a mean of zero 
Removed duplicates. and converted strings into numeric values
Dropped the name colmn and checked for multy coliniarity.

for after the cleaned i used knn regression and muliplte linear regression to predict the data using selling price as my target feature and age, kms driven and present price as my variables my model acturatle predicted the price of cars with a very low means error squared. knn performes the same way.

my predictions for this project were wrong the variples barley effect the change in price for selling price in cars.

