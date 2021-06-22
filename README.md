# Python Demo 
[Python Tuts](https://www.edureka.co/blog/data-structures-in-python/)
## 1. Write a Python Program to print Prime Numbers between 2 numbers
```Python
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
```
## 2. Write a Sort function to sort the elements in a list
## 3. Write a sorting function without using the list.sort function
nums = [10,5,6,20,15,4,8,2,1]
print(nums)
#nums.sort()
size = len(nums)
for x in range(size):
    for y in range(x+1, size):
        #print('num ', nums[x], nums[y])
        if(nums[x] > nums[y]):
            temp = nums[x];
            nums[x] = nums[y];
            nums[y] = temp;
print(nums)
