# Python-Combination formula
from math import*


def calculation(n,r):
    subtract= (n)- (r)    
    
    if n and r < 0:
        print("Factorial of negative is undefined")
        
     
    else:
        k=1
        fact_of_subtract=1
        while k<=subtract:
            
            fact_of_subtract=fact_of_subtract*k
            k=k+1   
    
        i=1
        fact_of_n=1
        while i<=n:
            fact_of_n=fact_of_n*i
            i=i+1
        
        j=1
        fact_of_r=1
        while j<=r:
            fact_of_r=fact_of_r*j
            j=j+1 
          
        product=(fact_of_r)*(fact_of_subtract)
        
        c=fact_of_n/product
        print(f"Value of combinations is {c}")
    
