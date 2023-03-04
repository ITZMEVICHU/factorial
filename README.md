# factorial

Python Program for factorial of a number using function, loop and if else conditions.
For example factorial of 5 is 5*4*3*2*1 which is 120
Input =5
Output =120




Code:


num = int(input("Enter a number: "))    
factorial = 1    
if num < 0:    
   print(" Factorial does not exist for negative numbers")    
elif num == 0:    
   print("The factorial of 0 is 1")    
else:    
   for i in range(1,num + 1):    
       factorial = factorial*i    
   print("The factorial of",num,"is",factorial)  


Output:
Enter a number: 5
The factorial of 5 is 120
