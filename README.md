# conditionals
#program to print all prime number in between 1 to 100. print("Prime numbers between 1 and 100 are : ") for i in range(1,100):         #For Loop to iterate a loop between 1 and 100 values     count = 0     for j in range(2,(i//2)+1): #For Loop to check whether the number is divisible or not         #If divisible, increment the count, and break statement skip that number         if i%j ==0:             count = count+1             break                 # checks whether the count is zero, and the given number is not equal to 1. If it is true, number is primeand print it     if( count==0 and i!= 1):         print(i)                  
