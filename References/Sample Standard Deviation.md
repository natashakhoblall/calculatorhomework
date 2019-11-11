Standard deviation measures the spread of a data distribution. It measures the typical distance between each data point and the mean.


Python Code: Proportion function of Statistics Module 
  
from math import *
from numpy import *
from datascience import *
from scipy import stats

  
Creating a sample of data 
sample = [2.74, 1.23, 2.63, 2.22, 3, 1.98] 
  
# Prints statistics function for standard deviation of the sample 
# Function will automatically calculate based on the imported statistics function listed below

print(statistics.pstdev(sample))


Reference: Geeks for Geeks
      
   
