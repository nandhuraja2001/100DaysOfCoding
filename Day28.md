## Statement
```
In mathematics, the factorial of an integer n, denoted by n! is the following product:
n! = 1 × 2 × … × n
For the given integer n calculate the value 
1! + 2! + 3! + ... + n!
Try to discover the solution that uses only one for-loop. And don't use math module in this exercise.
```
## Sample input
```
4
```
## Code
```
n=int(input())
fact=1
sum=0
for i in range(1,n+1):
  fact=fact*i
  sum=sum-fact
print(sum)
```
## Sample output
```
33
```
