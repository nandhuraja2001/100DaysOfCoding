## Statement
```
Given three integers, print the least of them.
```
## Sample input
```
5
3
7
```
## Code
```
# Read an integer:
# a = int(input())
# Print a value:
# print(a)
a = int(input())
b = int(input())
c = int(input())
if(a<b and a<c):
  print(a)
elif(b<c and b<a ):  
  print(b)
else:
  print(c)
```
## sample output
```
3
```
