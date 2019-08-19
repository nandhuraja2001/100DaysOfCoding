## Statement
```
It is possible to place 8 queens on an 8×8 chessboard so that no two queens threaten each other. 
Thus, it requires that no two queens share the same row, column, or diagonal.  
Given a placement of 8 queens on the chessboard. 
If there is a pair of queens that violates this rule, print YES, otherwise print NO. 
The input consists of eight coordinate pairs, one pair per line, 
with each pair giving the position of a queen on a standard chessboard with rows and columns numbered from 1 to 8.
```
## Sample input
```
1 5
2 3
3 1
4 7
5 2
6 8
7 6
8 4
```
## Code
```
row=[]
column=[]
n=8
for i in range(n):
  a,b = [int(s) for s in input().split()]
  row.append(int(a))
  column.append(int(b))

result=1
for i in range(n):
  for j in range(i+1,n):
    if(row[i]==row[j] or column[i]==column[j] or abs(row[i]-row[j])==abs(column[i]-column[j])):
      result=0
if result:    
  print("NO")
else:
  print("YES")
```
## Sample output
```
NO
```
