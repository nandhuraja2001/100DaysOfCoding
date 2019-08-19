## Statement
```
Given a list of numbers with all elements sorted in ascending order, determine and print the number of distinct elements in it.
```
## Sample input
```
1 2 2 3 3 3
```
## Code
```
count=1
a=[int(i) for i in input().split()]
for j in range(1, len(a)):
  if a[j-1]!=a[j]:
    count += 1
print(count)
```
## Sample output
```
3
```
