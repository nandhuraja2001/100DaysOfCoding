## Statement
```
Given a list of numbers, determine and print the number of elements that are greater than both of their neighbors.
The first and the last items of the list shouldn't be considered because they don't have two neighbors.
```
## Sample input
```
1 5 1 5 1
```
## Code
```
a=[int(i) for i in input().split()]
count=0
for j in range(1,len(a)-1):
  if(a[j-1]<a[j]>a[j+1]):
    count+=1
print(count)
```
## Sample output
```
2
```
