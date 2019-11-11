A proportion refers to the fraction of the total that possesses a certain attribute.


Python Code: Proportion function of Statistics Module 
  
from math import *
from numpy import *
from datascience import *
from scipy import stats



  
Creating a sample of data 
sample = [2.74, 1.23, 2.63, 2.22, 3, 1.98] 
  
# Prints datascience function proportion of the sample 
# Function will automatically calculate based on the imported datascience function listed below

print(datascience.util.sample_proportions(sample, 6))


Reference: Geeks for Geeks
      
   
