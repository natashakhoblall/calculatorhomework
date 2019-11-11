The sample proportion is the fraction of samples which were successes or positive

Python Code: Variation of Sample Proportion function from Statistics Module 
  
from math import *
from numpy import *
from datascience import *
from scipy import stats

  
Creating a sample of data 
sample = [2.74, 1.23, 2.63, 2.22, 3, 1.98] 
  
# Prints statistics function for sample proportions of the sample 
# Function will automatically calculate based on the imported datascience function/utility listed below

print(datascience.util.sample_proportions(sample))


Reference: Geeks for Geeks
      
   
