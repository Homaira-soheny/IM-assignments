Big-O notation measures the order of growth of a running time. It expresses the 
complexity of an algorithm. The complexity of an algorithm means the steps required to execute an algorithm.

We have 5 algorithm and to explain which one is the best we need to know their running time complexity.

Let, n = 4 #input size
     k = 4 #a constant
     y = running time

#A logarithmic algorithm – O(logn)
    y = log(4)  # base 2
    y = 2.0 # 2 steps
    
Here, Runtime grows logarithmically in proportion to n. 
    

#A linear algorithm – O(n) 
   y = n
   y = 4 # 4 steps are needed 

Here, Runtime grows directly in proportion to n. 


#A quadratic algorithm – O(n^2)
   y = 4^2
   y = 16 # 16 steps are needed
   
Here, Runtime grows in proportion to n^2


#A cubic algorithm – O(n^3)
   y = 4^3
   y = 64 # 64 steps are needed
   
Here, Runtime grows directly in proportion to n^3.


#A polynomial algorithm – O(n^k)

   y = (4^4) 
   y = 256  # 256 steps are needed
   
Here, Runtime grows quicker than previous all based on n.   
   


From the value of y, we can see that, the performances(Runtimes) of different orders of algorithms separate rapidly as the input size(n)
gets larger (2.0 < 4 < 16 < 64 < 256).
   

So, we can say logarithmic algorithm is the best among these 5 algorithms.















