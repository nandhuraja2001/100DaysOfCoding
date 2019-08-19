## Statement
```
Given a list of numbers, find and print all its elements with even indices (i.e. A[0], A[2], A[4], ...).
```
## Sample input
```
5 6 7 8 9
```
## Code
```
a=[int(i) for i in input().split()]
print(a[0: :2])
```
## Sample output
```
5 7 9
```
