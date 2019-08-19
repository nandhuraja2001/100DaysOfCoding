## Statement
```
Given a list of numbers, find and print all its elements that are greater than their left neighbor.
```
## Sample input
```
1 5 2 4 3
```
## Code
```
a=[int(i) for i in input().split()]
j=0
while j<len(a):
  if(a[j]>a[j-1] and j>0):
    print(a[j],end="")
  j+=1    
```
## Sample output
```
5 4
```
