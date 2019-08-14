## Statement
```
Given a sequence of distinct non-negative integers, where each number is written in a separate line. 
The sequence ends with 0. Print the second largest element in this sequence. It is guaranteed that the sequence has at least two elements.
```
## Sample input
```
1
7
9
0
```
## Code
```
a=1
b=1
number=1
b=0
while number!=0:
  number=int(input())
  if b<number<a:
     b=number
  elif number>a:
    b=a
    a=number
print(b)
```
## Sample output
```
7
```

