Population Standard Deviation measures the dispersion of numbers in a group are spread out from each other - calculated by obtaining the mean and subtracting it from each number in the list and then squaring each number, then calculating the mean of the squared numbers and taking the square root

Standard Deviation = √( (&Sum;(F x M2 – n x μ2)) / (n-1) )


Python Code: stdev() function 
  
# importing Statistics module 
import statistics 
  
# creating a simple data - set 
sample = [1, 2, 3, 4, 5] 
  
# Prints standard deviation 
# xbar is set to default value of 1 
print("Standard Deviation of sample is % s " 
                % (statistics.stdev(sample))) 

stdev of the sample = 1.5811388300841898


Reference: Geeks for Geeks
