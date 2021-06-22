# Python Demo
## 1. Write a Python Program to print Prime Numbers between 2 numbers
'''
def solution(start, end):
    for n in range(start, end):
        if(isPrime(n)):
            print('num ', n )
def isPrime(n):
    if(n > 1):
        for i in range(2, n):
            if(n % i == 0):
                return False
        return True
"""
  n = 5
  for i in 2 to 5
     1. 5%2
     2. 5%3
     3. 5%4
     4. 5%5=0
"""
solution(10, 50)
'''
## 2. Write a Sort function to sort the elements in a list
