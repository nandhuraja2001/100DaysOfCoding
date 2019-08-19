## Statement
```
Given a list of distinct numbers, swap the minimum and the maximum and print the resulting list.
```
## Sample input
```
3 4 5 2 1
```
## Code
```
a=[int(i) for i in input().split()]
minimum=a.index(min(a))
maximum=a.index(max(a))
a[minimum],a[maximum]=a[maximum],a[minimum]
print(a)
```
## Sample output
```
3 4 1 2 5
```
