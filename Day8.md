## Statement
```
N students take K apples and distribute them among each other evenly. The remaining (the indivisible) part remains in the basket. 
How many apples will each single student get? How many apples will remain in the basket?
The program reads the numbers N and K. It should print the two answers for the questions above.
```
## Sample input
```
6
50
```
## Code
```
# Read the numbers like this:
# n = int(input())
# Print the result with print()
# Example of division, integer division and remainder:
# See output below for actual values 
n = int(input())
k = int(input())
print(k // n)   # example of integer division
print(k % n)    # example of remainder calculation 
```
## Sample output
```
8
2
```
