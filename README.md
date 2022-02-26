# JOB-A-THON-Approach
Approach Description
Pre-Processing
Converted Date variable into integers value(Count, month, day, year, hour, min, dayofweek) (i.e. Dateofjoining)

One Hot Encoded categorical Value (i.e. Gender, Education_Level)

##New Features (Information extraction):-

Emp_tenure:- Calculated Employe tenure (number of days in the company)

Min Bussiness Value:- This feature represent Min Business Value of an Employee.

With the help of feature LastWorkingDate, labled the data whether an employe got churned, and I stored that information in Attrition column.

I dropped few features like LastWorkingDate, MMM-YYY etc

After that I separated test data(As panels requested Employees will be Churned or not) from training data (separated train and test data)

Upsampled the Imbalanced Dataset using SMOTE.

Finally I used Random Forest algorithm with Hyper Parameter tuning for prediction.
