## Statement
```
Given a list of numbers, find and print the elements that appear in it only once. 
Such elements should be printed in the order in which they occur in the original list.
```
## Sample input
```
4 3 5 2 5 1 3 5
```
## Code
```
a = [int(s) for s in input().split()]
for i in range(len(a)):
  for j in range(len(a)):
    if i != j and a[i] == a[j]:
        break
  else:
    print(a[i], end=' ')
```
## Sample output
```
4 2 1
```
