## Statement
```
For the given integer N calculate the following sum:
1³ + 2³ + ... + N³
```
## Sample input
```
3
```
## Code
N=int(input())
result=0
for N in range(1,N+1):
  result += N**3
print(result)
```
## Sample output
```
36
```
