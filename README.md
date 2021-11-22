# JOB-A-THON-Approach
Approach Description
Pre-Processing
Converted Date variable into integers value (ie Dateofjoining)
One Hot Encoded categorical Value (ie Gender, Education_Level)

##New Features (Information extraction):-

emp_tenure:- Calculated Employe tenure (number of days in the company)

Min Bussiness Value:- This feature represent difference of Min Business Value of an Employee.

With the help of feature LastWorkingDate, I calculated whether an employe got churned, and I stored that information in Attrition column.

I dropped few features like LastWorkingDate, MMM-YYY etc

After that I separated test data(As panels requested Employees will be Churned or not) from training data (separated train and test data)

Upsampled the Imbalanced Dataset.

Finally I used Random Forest algorithm with Hyper Parameter tuning for prediction.
