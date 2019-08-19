## Statement
```
Given a list of non-zero integers, 
find and print the first adjacent pair of elements that have the same sign. If there is no such pair, print 0.
```
## Sample input 1
```
-1 2 3 -1 -2
```
## Sample input 2
```
1 -3 4 -2 1
```
## Code
```
a=input()
b=list(map(int,a.split()))
i=1
for i in range(1, len(b)):
  if b[i]*b[i-1] > 0:
    print(str(b[i-1]),str(b[i]))
    break
  elif i==len(b)-1:
    print("0")
```
## Sample output 1
```
2 3
```
## Sample output 2
```
0
```
