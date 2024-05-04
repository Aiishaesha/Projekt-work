
import math                
# Importing math module for math.ceil() function (rounding up).

# Monthly fee in USD
MonthlyFee = 38            

# Course length according to Coursera in months
CourseLength = 11          

# The coefficient which shows how much times faster you can pass the course
MyPace = 3                 

# Calculating the total fee
TotalFee = math.ceil(CourseLength / MyPace) * MonthlyFee 

# Outputting the total fee
print('For the Data Science course, you will pay a total of', TotalFee, '$.')
