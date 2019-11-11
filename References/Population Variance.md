Population variance tells us how data points in a specific population are spread out. 
Essentially, it is the average of the distances from each data point in the population to the mean squared. 


Python Code: Population_variance() function of Statistics Module 
  
from math import *
from numpy import *
from scipy import stats



  
Creating a sample of data 
sample = [2.74, 1.23, 2.63, 2.22, 3, 1.98] 
  
# Prints variance of the sample 
# Function will automatically calculate 

print(statistics.variance(sample)) 



Reference: Geeks for Geeks
      
   
